# Website Research & Implementation Plan — FELOH Ecosystem
**Research date:** 2026-10-26  
**Status:** RESEARCH / IMPLEMENTATION PLAN — not a deployment attestation  
**Canonical architecture:** `FELOH → NAKEBUSEN → NAKEBUSEN LOCS + NAKEBUSEN DIGITAL`

## 1. Executive decision

Use the existing public site at [donfelohke.github.io](https://donfelohke.github.io/) as the single lightweight public entry point for the first iteration. Keep it static, text-first, accessible, mobile-first, low-dependency and easy to maintain. The public website is a view of the ecosystem, not the canonical knowledge base.

- **NAKEBUSEN** is the parent enterprise and sole commercial/customer transaction interface.
- **NAKEBUSEN LOCS** is the customer-facing loc craft and beauty-services path.
- **NAKEBUSEN DIGITAL** is the technical-services path; **WARENA** is its technical identity, and **WARENA Systems** describes systems engineering and infrastructure.
- **IKAI Mirror / IKAI REFLECTIVE (IR-01)** is research, not a released product.
- **GENJE ZA WARENA — THE FIRE OF THE FORMIDABLE** is cultural identity and motivating idea, not a separate commercial division.
- **FELOH / @donfelohke / #HisGenjeness** is the human author and integrated practice.
- **Gallery** is a separately curated asset destination with provenance and rights review.

Keep the rule “ONLY NAKEBUSEN TRANSACTS” as internal architecture guidance; do not expose it as public-facing slogan copy. Website enquiries are not confirmed appointments or payment transactions.

## 2. Evidence classes

This document separates:
- **Repository-verified:** directly inspected via connected GitHub repository tools on the research date.
- **Web-source evidence:** information published by the linked source; it may still need independent confirmation.
- **Owner-supplied/canonical:** current architecture, campaign pricing and constraints supplied in the project corpus.
- **Recommendation:** proposed next action, not evidence of implementation.
- **Unknown:** requires a test, owner confirmation or further source inspection.

A repository README, commit or successful static check does not prove live behaviour, deployment, business availability or a successful real-world customer journey.

## 3. Existing implementation audit

### Verified repository facts
The connected GitHub account exposes these public repositories:
- [donfelohke.github.io](https://github.com/donfelohke/donfelohke.github.io) — public site; default branch `main`.
- [feloh-corpus](https://github.com/donfelohke/feloh-corpus) — shared canon and decision provenance.
- [NAKEBUSEN](https://github.com/donfelohke/NAKEBUSEN) — enterprise and operating documentation.
- [WARENA](https://github.com/donfelohke/WARENA) — systems and reproducibility documentation.
- [Ikai](https://github.com/donfelohke/Ikai) — reflective-compute research.
- [Genje](https://github.com/donfelohke/Genje) — creative technology and embodied practice.
- [Gallery](https://github.com/donfelohke/Gallery) — curated assets and rights review.
- [donfelohke](https://github.com/donfelohke/donfelohke) — profile and repository navigation.

The public site repository README documents static HTML/CSS, no build system, no embedded graphics, no analytics/trackers/external fonts by default, crawl files, tests and GitHub Actions. Its `index.html` was inspected on 2026-10-26. It currently presents Locs, Digital, GENJE, founder and contact sections; a theme toggle; service starting prices; WhatsApp enquiry links; Organization JSON-LD; canonical/Open Graph/Twitter metadata; and no embedded images. The test file `tests/test_site.py` checks document structure, metadata, internal anchors, no-graphics policy, contact links, service tokens, robots/sitemap and booking-boundary copy.

### Risks / gaps identified from source inspection
1. **Language toggle:** the README specifies an English-default Kiswahili/English toggle, but the inspected `index.html` contains no language toggle or translated page content. Treat this as a documented requirement not yet evidenced in the page.
2. **Service-price consistency:** site HTML currently lists Retouch & Styling from KES 700, Sisterlocs Retie from KES 1,500 and Artificial Locs Install from KES 3,500. Canonical policy confirms the current Eldoret campaign figures KES 700 and KES 3,500; Sisterlocs KES 1,500 and other older prices require current owner confirmation before continued publication.
3. **Scope language:** technical service copy should be reviewed against the services actually deliverable today. Repository documentation explicitly says the proposed playbooks do not prove every service is available or deployed.
4. **Public email:** the inspected HTML contains a public email address in both structured data and a mailto link. Confirm this is intentionally public and current before retaining it.
5. **Photography:** repository documentation says no approved client/service or technical/creative portfolio photos were present at the documented audit. Maintain the no-embedded-graphics rule unless the owner changes it through a reviewed decision. Do not present generated or stock imagery as actual client evidence.
6. **Live checks:** repository source inspection does not establish current live deployment, visual rendering, workflow status, DNS/HTTPS state, or mobile-device behaviour. Those remain to be tested and recorded.
7. **SEO metadata:** metadata describes loc care and practical technology but is broad. Revisit title/description once location, services and language scope are owner-confirmed; avoid keyword stuffing or claims of guaranteed rankings.

## 4. Public website strategy

### Recommended information architecture
Keep the first release focused and avoid splitting the audience across multiple competing commercial brands.

1. **Home:** clear identity, two paths (Locs / Digital), geographic context, one primary next action.
2. **Locs:** current service scope, transparent starting prices, what affects final quotes, location/availability confirmation, approved work evidence if available, WhatsApp booking request.
3. **Digital / WARENA Systems:** a concise service menu, who the service is for, scope/discovery process, delivery evidence, and enquiry CTA routed through NAKEBUSEN.
4. **IKAI:** a short research note stating purpose, principles, data boundaries and maturity; explicitly not a released product.
5. **GENJE ZA WARENA:** cultural identity and creative practice; distinguish attested linguistic research from intended brand meanings.
6. **Founder / practice:** concise, owner-approved biography and public links.
7. **Contact:** approved contact channel, service location context, clear statement that enquiry is not confirmation.

Do not add online checkout, automated booking confirmation, customer accounts, tracking pixels or forms that imply capabilities not implemented. Add functionality only after operational, privacy and support requirements are documented.

### NAKEBUSEN Locs conversion priorities
- Make the two approved campaign prices easy to find: Retouch & Styling — KES 700; Artificial Locs Installation — KES 3,500.
- Label them as current campaign/starting prices only if owner reconfirms the campaign is active; never silently replace KES 700 with historical KES 800.
- Clearly list what is offered; no shaving or braiding.
- Keep WhatsApp/call actions accessible, but explain that availability, final quote, location and timing are confirmed directly.
- Use real approved photos only if asset rights, customer consent, provenance and intended use are recorded in Gallery.
- Keep location details and public contact consistent across site, Google Business Profile and social profiles; do not publish a home address unless explicitly intended.

### WARENA / Digital credibility
- Separate service offerings from internal tools and research inventory.
- Use case studies only when there is actual implementation evidence and permission to publish.
- For each technical example, state problem, constraints, chosen approach, test/verification evidence, limitations and status.
- Mark services as offered only after the owner confirms current capacity, scope, price basis and support obligations.
- Avoid claims like “secure,” “reproducible,” “production-ready” or “fully local” without evidence and a defined test.

### IKAI / GENJE editorial boundaries
- IKAI: “Human Remains Author; Mirror ≠ Judge; Local First.” No face identification, diagnosis, beauty scoring, person ranking, hidden profiling, covert surveillance or autonomous authorization as default features. Publish only research status supported by evidence.
- GENJE ZA WARENA: “The Fire of the Formidable.” Present as cultural identity and intended brand meaning. Treat “Genje,” “Za,” “Warena” and “Genjeness” as language-research questions; cite source, date, dialect and context, and distinguish attested usage from author-supplied interpretation.

## 5. Competitive website research

A preliminary public-web scan of loc-service websites found these patterns:

- [Flo Sisterlocks](https://www.flosisterlock.co.ke/): specialist positioning, consultation/appointment path, service details and starting prices. The site describes itself as focused on Sisterlocks and small-loc services, with nails/extensions as additional categories.
- [Locks Parlor](https://locksparlor.co.ke/): broad service catalogue, visible booking CTA, contact/location information and service imagery.
- [Joy Sisterlocks](https://joysisterlocks.co.ke/): specialist expertise, installation/maintenance process, customer education and a WhatsApp-led consultation flow.
- [KJ Salon](https://kjsalon.co.ke/services/natural-hair): local Eldoret context, service-category pages and appointment enquiry path.
- [Astro’s Locs Center Eldoret listing](https://www.findglocal.com/KE/Eldoret/116727936782858/Astro%E2%80%99s-Locs-Center-Eldoret): public listing and social posts used to promote loc installation/maintenance; it is not equivalent to a fully audited official website.

These examples are not a statistically representative market survey, and their public claims have not all been independently verified. They are useful comparative observations, not proof of competitor quality or business performance.

### Differentiation opportunity
Do not imitate generic “luxury salon” language or try to match every competitor service. Differentiate through:
- focused loc craft and honest scope;
- clear current starting prices and direct booking communication;
- proof of root structure, clean parting and finish when approved evidence becomes available;
- the distinctive NAKEBUSEN relationship between craft, technology and culture;
- clear boundaries between a commercial service, technical practice, research project and creative identity.

## 6. Technology and deployment recommendation

### Default: preserve the existing static-site architecture
For the current brochure/portfolio stage, static HTML/CSS/JavaScript is proportionate. It is low-complexity, inspectable, inexpensive to host and does not require a database or server-side booking stack. Continue with the existing dependency-free tests and GitHub Actions unless a concrete requirement justifies a framework.

### Hosting options
- **GitHub Pages:** appropriate for a static public site and supports custom domains and HTTPS. GitHub warns that Pages should not be used for sensitive transactions such as passwords or credit-card data. Source: https://docs.github.com/en/pages/getting-started-with-github-pages/securing-your-github-pages-site-with-https
- **Custom domain:** desirable when the owner has selected and registered a domain. Verify the domain in GitHub before attaching it, configure DNS carefully, and enforce HTTPS. Source: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/about-custom-domains-and-github-pages
- **Dynamic booking or payments:** do not implement on GitHub Pages alone. If later required, perform a separate threat model, privacy review, provider comparison and operations plan; never store payment credentials or sensitive customer records in Git.

### Mobile and SEO
Google documents mobile-first indexing and recommends mobile-friendly implementation; responsive design is generally the easiest pattern to maintain. Source: https://developers.google.com/search/docs/crawling-indexing/mobile/mobile-sites-mobile-first-indexing

Google's SEO Starter Guide emphasizes useful content, descriptive URLs and clear page organization rather than guaranteed rankings. Source: https://developers.google.com/search/docs/fundamentals/seo-starter-guide

Recommended technical checklist:
- responsive layout, semantic headings and keyboard-visible focus;
- descriptive page title, meta description and canonical URL;
- valid Organization/LocalBusiness structured data only for accurate claims;
- correct robots.txt and sitemap.xml;
- no broken internal links or mixed-content resources;
- test narrow screens and slow connections;
- validate outbound WhatsApp, telephone and email links;
- review accessibility, contrast, keyboard navigation and reduced-motion behaviour;
- use Search Console after launch and a Google Business Profile only where eligible and accurate;
- no analytics/tracking unless the owner explicitly approves a privacy-conscious measurement plan.

## 7. GitHub integration plan

### Repository responsibilities
- `donfelohke.github.io`: public website implementation and its tests.
- `feloh-corpus`: canonical architecture, research sources, cross-project decisions and implementation plan.
- `NAKEBUSEN`: service catalogue, business operations, customer/privacy boundaries.
- `WARENA`: technical service definitions, systems architecture and evidence/runbooks.
- `Ikai`: research agenda, privacy model and prototype evidence.
- `Genje`: creative practice, cultural research, source provenance and release documentation.
- `Gallery`: asset manifest, permissions, consent and approvals.
- `donfelohke`: public profile and repository navigation.

### Proposed sequence
1. Record this plan in the corpus; keep it explicitly labelled as research/plan.
2. Create a focused issue in the website repository for an audit/remediation milestone.
3. Confirm current campaign validity, price publication, contact details, email publication, current service scope and language-toggle priority with the owner.
4. Build a branch and pull request; do not make a broad unreviewed redesign.
5. Update the HTML, tests and README together if the approved scope requires changes.
6. Run the repository's dependency-free site checks and any JavaScript/theme tests available in the repo.
7. Review GitHub Actions result, deployed URL, and a real mobile-browser view separately.
8. Record commit SHA, workflow run, test output, date, viewport/browser, and live URL in the delivery record. Mark deployment verified only when evidence exists.

### Acceptance criteria
- Public copy follows the current architecture and service exclusions.
- Only NAKEBUSEN is presented as the commercial customer/booking interface.
- Prices and contact details are current and owner-approved.
- No false booking/payment capability is implied.
- IKAI maturity and safety boundaries are explicit.
- GENJE brand interpretations are not represented as verified etymology.
- Public content is responsive, keyboard accessible and understandable on a phone.
- Site tests pass and links/metadata/crawl files are valid.
- Deployment and live rendering are recorded as separate verification steps.
- No secrets, private customer records, unapproved imagery or fabricated proof are committed.

## 8. Research source register

1. Google Search Central, “Mobile site and mobile-first indexing best practices”: https://developers.google.com/search/docs/crawling-indexing/mobile/mobile-sites-mobile-first-indexing
2. Google Search Central, “SEO Starter Guide”: https://developers.google.com/search/docs/fundamentals/seo-starter-guide
3. GitHub Docs, “Securing your GitHub Pages site with HTTPS”: https://docs.github.com/en/pages/getting-started-with-github-pages/securing-your-github-pages-site-with-https
4. GitHub Docs, “About custom domains and GitHub Pages”: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/about-custom-domains-and-github-pages
5. Flo Sisterlocks: https://www.flosisterlock.co.ke/
6. Locks Parlor: https://locksparlor.co.ke/
7. Joy Sisterlocks: https://joysisterlocks.co.ke/
8. KJ Salon natural hair services: https://kjsalon.co.ke/services/natural-hair
9. Astro’s Locs Center Eldoret public listing: https://www.findglocal.com/KE/Eldoret/116727936782858/Astro%E2%80%99s-Locs-Center-Eldoret
10. Canonical architecture and decision register: https://github.com/donfelohke/feloh-corpus/blob/main/docs/canonical-architecture-2026-10-26.md
11. Existing public website source: https://github.com/donfelohke/donfelohke.github.io/blob/main/index.html
12. Existing site checks: https://github.com/donfelohke/donfelohke.github.io/blob/main/tests/test_site.py

## 9. Explicit unknowns

- Current live website deployment/workflow status and mobile rendering were not verified by this document.
- Active status of the Eldoret campaign and all service availability must be owner-confirmed before publication.
- Current public email address should be reconfirmed.
- Custom domain ownership/selection is not established here.
- Competitor data is a preliminary public-web scan, not a complete competitive audit.
- No new site code was deployed as part of this research record.
