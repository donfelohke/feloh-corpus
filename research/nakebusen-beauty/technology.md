# NAKEBUSEN Technology Research Dossier

**Status:** Architecture proposal / research scaffold  
**Prepared:** 26 October 2026  
**Business context:** NAKEBUSEN loc-care practice; primary market Eldoret, Kenya  
**Technology relationship:** WARENA / NAKEBUSEN DIGITAL  
**Guiding principle:** Freedom Is a System.

> This document is a proposed architecture, not a report of an implemented or security-tested system. Product features and licences must be checked against current upstream documentation before adoption. Business workflows, contact details, prices and legal obligations require owner confirmation.

## 1. Executive recommendation

Do not begin by building a custom salon-management platform. Begin with the simplest maintainable workflow that reliably converts enquiries into confirmed appointments, supports excellent service, records only necessary information, and lets the business export its data.

### Recommended sequence

1. **Establish a dependable website:** fast mobile-first pages, service descriptions, confirmed prices, location/booking instructions, accessible typography, English default and persistent Kiswahili toggle.
2. **Keep booking human-confirmed initially:** use a direct enquiry channel while availability, appointment duration, cancellation rules and client volume are validated. Clearly state that an enquiry is not yet a confirmed appointment.
3. **Use a small, controlled appointment register:** store only the minimum information needed to run the business; restrict device access and keep encrypted backups where feasible.
4. **Measure the funnel:** enquiries, response time, confirmed appointments, completed visits, cancellations/no-shows and repeat visits. Avoid collecting demographic or health details without a defined need and appropriate safeguards.
5. **Evaluate open-source booking software only when the manual workflow becomes a bottleneck.** Test on dummy data first; verify mobile usability, licence, security updates, exportability, backups, reminders and the cost of hosting and maintenance.
6. **Integrate with WARENA gradually:** version-controlled configuration, documented recovery, reproducible deployment where practical, and clear separation between the public website and sensitive customer records.

## 2. Requirements

### Functional requirements

- Public service catalogue with accurate scope, prices, appointment expectations and exclusions.
- Mobile-first display at narrow widths; usable on low-end Android devices and slower networks.
- English and Kiswahili content with a visible, persistent language control.
- Clear call-to-action to enquire or request an appointment.
- Human confirmation until real availability and booking rules are implemented.
- Internal appointment status: requested, confirmed, completed, cancelled, or no-show.
- Export of appointments and business data in a documented, portable format.
- Optional reminders only after channel costs, consent, delivery failures and operational responsibilities are understood.
- Accessible navigation, keyboard focus, adequate contrast, meaningful link labels and reduced dependence on animation.
- A simple owner workflow that does not require a full-time administrator.

### Non-functional requirements

- **Reliability:** a documented manual fallback if hosting, power, connectivity or a messaging service fails.
- **Privacy:** minimum necessary collection, defined purpose, limited access and a retention/deletion process.
- **Security:** HTTPS for public services; strong unique credentials; least privilege; updates; protected backups; no secrets in Git.
- **Portability:** readable exports, documented formats, and a tested way to restore records.
- **Maintainability:** small components, clear documentation, version control and a rollback path.
- **Cost transparency:** include hosting, domain, backups, messaging, payment charges, maintenance time and any vendor subscription.
- **Evidence:** test on real devices and representative connections; do not claim performance, accessibility or security without testing.

## 3. Architecture: separate public experience from private operations

```text
Client
  |
  v
Public NAKEBUSEN website
  |-- service catalogue and prices
  |-- English / Kiswahili content
  |-- contact / booking instructions
  |
  v
Booking intake (manual first)
  |-- enquiry
  |-- availability check
  |-- human confirmation
  |
  v
Private appointment register
  |-- minimum contact details
  |-- appointment and service
  |-- status and necessary notes
  |
  +--> aggregate business metrics (no unnecessary personal data)

WARENA operations:
version control | backups | restore test | documentation | monitoring
```

Do not expose the appointment register, customer notes, or administration interface through the public static website. Do not commit customer data, API tokens, passwords, private photographs, or production database snapshots to the repository.

## 4. Technology options to investigate

These are candidates for a controlled evaluation, not automatic recommendations or endorsements. Upstream repositories and deployment requirements can change.

### Option A — static website + human-confirmed enquiries

**Best initial fit if appointment volume is manageable.**

- Static HTML/CSS/JavaScript or the existing website stack.
- Published services and price list; tested contact link; clear response and confirmation expectations.
- A private, access-controlled appointment register with a regular backup and export.
- Low operating complexity; no new customer-data application required at launch.

**Limitations:** manual availability checks, reminders and metrics; the business must respond consistently. Never represent a message link as a functioning booking engine.

### Option B — Easy!Appointments

- Project: https://github.com/alextselegidis/easyappointments
- Official site: https://easyappointments.org/
- **Why investigate:** established open-source appointment scheduler with services, providers, working hours and customer appointment flows.
- **Architecture to check:** PHP and database requirements, installation/upgrade process, email configuration, export/API options, backup/restore and supported translations.
- **Licence:** verify the current repository licence and obligations before adapting or distributing a modified version.
- **Decision gate:** test booking, cancellation, permissions, mobile screens, email delivery, restore and data export in a non-production environment.

### Option C — OpenSalon

- Project: https://github.com/clawnify/OpenSalon
- **Why investigate:** its repository describes a locally runnable salon-management application using SQLite, with appointment scheduling, clients, services and inventory.
- **Important caveat:** repository claims such as “production-ready” are not independent security or reliability certification. Confirm the current licence, release activity, external dependencies, booking exposure, authentication and backup behaviour directly in the repository.
- **Decision gate:** do not place real client data in it until its current maturity, security posture, maintenance status and licence are independently reviewed.

### Option D — Lumina

- Project: https://github.com/effuselabs/lumina
- **Why investigate:** open-source salon/barbershop booking, client, staff and financial workflow.
- **Important caveat:** its repository describes it as pre-release and not yet suitable for real salon customers. Use as a design/research reference only until maintainers document production readiness and the system passes independent evaluation.

### Comparison

| Criterion | Option A: static + manual | Easy!Appointments | OpenSalon | Lumina |
|---|---|---|---|---|
| Setup complexity | Low | Medium | Medium / verify | Medium / verify |
| Customer self-booking | No; enquiry only | Candidate feature; test | Verify current implementation | Booking loop reported; not production-ready per project |
| Private client records | Separate manual register | Application database | Application database | Application database |
| Offline/local operation | Website can be static; private register choice matters | Server-dependent; verify setup | Project describes local SQLite operation | Server/database dependent |
| Maintenance burden | Low | Medium | Unknown until review | Elevated while pre-release |
| Current recommendation | Start here if volume allows | Evaluate when needed | Prototype only until verified | Research only |

**Selection rule:** choose the smallest system that meets a demonstrated business need and that the owner can back up, update, restore and leave. Open source alone does not guarantee security, usability, sovereignty or long-term maintenance.

## 5. Data model and data minimisation

Start with the smallest useful records.

### Appointment record

- Random internal appointment identifier.
- Client name and one necessary contact method.
- Requested/confirmed date and time.
- Service requested and agreed price.
- Status and operational timestamps.
- Only notes necessary to fulfil the appointment.

### Optional information requiring a separate justification

- Style reference images.
- Accessibility or service-accommodation details.
- Product sensitivities or scalp-related notes.

These can reveal personal or health-related information. Do not collect them by default. If needed, explain the purpose, restrict access, set retention limits, and consider whether the practitioner can simply ask the client at the appointment rather than retaining the information.

### Avoid collecting

- National ID, exact home address, date of birth, family details, unrelated health history, or demographic profiles unless a specific lawful and necessary purpose is established.
- Client images as a condition of booking.
- Contact lists for unsolicited marketing.
- Sensitive details in general-purpose analytics, URL parameters, public issue trackers, or Git commits.

## 6. Privacy and Kenya compliance research

The Office of the Data Protection Commissioner (ODPC) describes data-subject rights including being informed about the use of personal data, access, objection and correction/deletion rights in relevant circumstances. Review the current official material and applicable law before designing the workflow:

- ODPC — Rights of a Data Subject: https://www.odpc.go.ke/rights-of-a-data-subject/
- ODPC official portal: https://www.odpc.go.ke/
- Kenya Law — official legislation database: https://new.kenyalaw.org/

This dossier is not legal advice. Before implementation, assess whether the business's data processing and size/type of activity trigger registration or other requirements; establish an appropriate privacy notice, lawful purpose, retention schedule, access controls, breach response and procedures for data-subject requests. Do not assume that small size automatically exempts a business.

### Practical privacy checklist

- [ ] State what information is collected and why.
- [ ] Collect the minimum needed for booking and service delivery.
- [ ] Explain how clients can ask for access or correction and how deletion requests are handled.
- [ ] Separate appointment administration from optional promotional consent.
- [ ] Ask separately before publishing a client photo, testimonial, or before/after image.
- [ ] Limit who can access the records and protect devices with screen locks and updates.
- [ ] Set a retention period and delete information no longer needed, subject to legitimate recordkeeping obligations.
- [ ] Review third-party processors, hosting location, messaging integrations and international transfers.
- [ ] Keep a simple incident-response plan.
- [ ] Test a restore from backup and document the result.

## 7. Security, backup and recovery

Minimum operating standard:

1. Use a unique password for every administrative account and multi-factor authentication where supported.
2. Keep software, dependencies, hosting components and device operating systems updated.
3. Use HTTPS for all public pages and application traffic.
4. Restrict administrative routes; do not rely on a hidden URL as access control.
5. Keep production secrets outside Git and public frontend bundles.
6. Back up private records on a defined schedule to a protected location separate from the primary device/server.
7. Encrypt backups where practical and keep the decryption key separate.
8. Test restore periodically using a documented procedure.
9. Define a manual fallback for outages and reconcile any temporary paper/offline records afterwards.
10. Record the date, method and outcome of the last restore test.

For a low-volume business, a well-protected and tested manual process may be safer than an unmaintained server exposed to the internet.

## 8. Website and conversion instrumentation

Measure the booking journey without invasive tracking.

### Funnel

```Visitor
  -> Service/pricing page viewed
  -> Booking/contact action selected
  -> Enquiry received
  -> Appointment confirmed
  -> Appointment completed
  -> Repeat appointment
```

### Minimum metrics

- Enquiries per week and source (client-reported or coarse channel counts).
- Median response time during business hours.
- Confirmed bookings / valid enquiries.
- Completed appointments / confirmed bookings.
- Cancellation and no-show rates.
- Repeat appointments over a defined period.
- Revenue and direct costs by service.
- Time spent per service and effective revenue per working hour.

Avoid advertising pixels, cross-site profiling or session replay by default. Start with aggregate counts in a private spreadsheet or local report. Do not collect more personal data merely because an analytics tool supports it.

## 9. Operational workflow

### Before the appointment
- Client reads current service scope, price and conditions.
- Client submits an enquiry and preferred times.
- Practitioner checks availability and confirms the agreed appointment.
- Only necessary appointment details are recorded.

### During service
- Confirm the selected service and any agreed variation.
- Ask about comfort and adjust if the client reports pain or excessive tension.
- Keep optional photography separate from service delivery and obtain explicit permission.

### After service
- Provide appropriate practical aftercare guidance without unsubstantiated medical claims.
- Mark the appointment completed and record the agreed amount.
- Invite optional feedback without pressure.
- Send follow-up or promotional messages only under an appropriate, transparent process.

## 10. Acceptance tests before launch

### Public website
- [ ] Works at 320 px, 360 px, 390 px, 768 px and desktop widths.
- [ ] Navigation and theme/language controls do not overlap content.
- [ ] English/Kiswahili toggle works consistently and does not unexpectedly reset on navigation.
- [ ] Prices and service names match the owner-confirmed source of truth.
- [ ] Booking/contact link works on Android and desktop.
- [ ] Clear message explains that an enquiry is not confirmation.
- [ ] Keyboard navigation, visible focus, contrast and meaningful link labels checked.
- [ ] Images have appropriate permission, alternative text and sensible file sizes.
- [ ] No broken internal links, browser-console errors or accidental secrets.

### Booking system, if adopted
- [ ] Double-booking prevention tested.
- [ ] Time zone, business hours, breaks and cancellations tested.
- [ ] Unauthorised users cannot read or alter another client's record.
- [ ] Export contains the expected records and can be read independently.
- [ ] Backup restore succeeds in a test environment.
- [ ] Notifications are tested for delivery failure and do not leak unnecessary personal data.
- [ ] Updates, licence, support path and hosting cost documented.

No test should be marked passed until someone actually runs it and records evidence.

## 11. 30-day implementation roadmap

### Days 1–7: audit and baseline
- Inspect the current website repository, deployment and existing contact/booking flow before changing anything.
- Confirm operational facts with the owner.
- Map the current client journey and record baseline enquiry/booking counts.
- Check current hosting, domain, backup and access-control arrangements.

### Days 8–14: improve the simple path
- Fix mobile usability, service clarity, prices, contact links and bilingual navigation.
- Add a transparent human-confirmed booking process.
- Draft a concise privacy notice and client-image consent process for review.
- Validate changes on real devices and open a reviewable pull request.

### Days 15–21: controlled tooling evaluation
- Compare the manual process with Easy!Appointments and one local/self-hosted alternative.
- Test using dummy data, not live client records.
- Review licence, maintenance activity, authentication, exports, backups and restore.
- Document total cost and who will maintain the system.

### Days 22–30: decide based on evidence
- Keep the manual process if it works adequately.
- Pilot a booking application only if a measured operational bottleneck justifies it.
- Train the operator, document fallback and recovery, and review access.
- Publish only after owner approval and recorded verification.

## 12. Decisions required before implementation

1. Does NAKEBUSEN currently receive enough appointment requests for online self-booking to be worth the maintenance?
2. Is human confirmation the preferred booking policy, or should a system expose live availability?
3. Who will administer updates, backups and recovery?
4. Which client data is genuinely necessary, and for how long?
5. Is the current website static GitHub Pages, another host, or a different deployment?
6. What operating budget is acceptable for domain, hosting, messaging and maintenance?
7. Is the Kiswahili translation reviewed by a fluent local speaker?
8. What legal and data-protection obligations apply to the actual operation?

## 13. References and further reading

- [Easy!Appointments repository](https://github.com/alextselegidis/easyappointments)
- [OpenSalon repository](https://github.com/clawnify/OpenSalon)
- [Lumina repository](https://github.com/effuselabs/lumina)
- [ODPC — Rights of a Data Subject](https://www.odpc.go.ke/rights-of-a-data-subject/)
- [ODPC](https://www.odpc.go.ke/)
- [Kenya Law](https://new.kenyalaw.org/)
- [NAKEBUSEN Beauty Research Dossier](../nakebusen-beauty/README.md)

## Final assessment

The appropriate starting system is not necessarily a custom app. It is a reliable service website, clear human-confirmed booking, minimal private records, tested backups, and measurable operations. Move to a booking application only when observed demand justifies the added software and security responsibilities.

**No implementation, penetration test, legal review, or production deployment is claimed by this document.**
