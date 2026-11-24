# Research programme: standards, evidence, benchmarks and local solutions

**Date:** 2026-11-24  
**Owner:** FELOH Corpus  
**Status:** RESEARCH PROGRAMME / SOURCE-GROUNDED INTAKE — not a completed literature review or implementation certification  
**Scope:** All ten repositories under `@donfelohke`  
**Principle:** Global references inform the work; local conditions determine what must be tested; measured evidence determines what may be claimed.

## 1. Purpose

This programme establishes a shared research method for the GitHub ecosystem. It connects international standards, primary research, technical manuals, public datasets, real deployments and case studies to the four practice domains and their supporting repositories.

It is not a proposal to create a new research repository or to duplicate specialist dossiers. FELOH Corpus owns shared research governance, source provenance, claim status and cross-project routing. Detailed technical research belongs in WARENA, IKAI, GENJE, NAKEBUSEN or the relevant support repository.

Every research output must answer:

1. What is the question, and what decision could the answer change?
2. What is already known from primary sources and existing implementations?
3. Which standards, laws, manuals or protocols apply, and are they normative, advisory, draft or historical?
4. What evidence supports each material claim?
5. What competing explanations, limitations or contradictory findings exist?
6. What changes under Kenyan / East African infrastructure, cost, language, policy, climate, labour, maintenance and access conditions?
7. What can be reused, adapted, interoperated with or locally tested before anything new is invented?
8. What would count as a successful, failed or inconclusive test?

## 2. Evidence discipline

Use the existing [Source Register](source-register.md), [Evidence and Editorial Standards](../EVIDENCE-AND-EDITORIAL-STANDARDS.md), and [Evidence and Provenance Method](../EVIDENCE-AND-PROVENANCE-METHOD.md).

### 2.1 Source hierarchy

Prefer, in order appropriate to the question:

- Legislation, official standards, normative specifications and official manuals.
- Primary datasets, original research papers, source repositories, release records and original technical reports.
- Peer-reviewed reviews, systematic reviews, independent evaluations and institutional case studies.
- Government, regulator, county, university and professional-body reports.
- Practitioner testimony, oral histories and field observations, with provenance and consent.
- Journalism and secondary commentary for context and discovery, not as sole support for technical or legal claims.

An official source is authoritative for what the institution published; it is not automatically an independent evaluation of outcomes. A vendor case study is evidence of a vendor-reported deployment, not a neutral benchmark.

### 2.2 Claim labels and maturity

Keep the Corpus vocabulary: **VERIFIED · CORROBORATED · DISPUTED · UNVERIFIED · INTERPRETATION · OPINION · TESTIMONY · PROPOSAL**.

Keep maturity distinct: **LIVE · PROTOTYPE · RESEARCH · CONCEPT · HISTORICAL · SUPERSEDED · UNKNOWN**.

A source being listed does not mean it has been read. A paper's reported result is not an independent replication. A specification is not a certification. A successful build is not field reliability. A research document is not a deployed capability.

### 2.3 Required evidence record

For every important claim, record:
- Claim ID and exact wording.
- Source ID, version/date, URL or immutable commit.
- Exact section, page, table, dataset field, code location or test log.
- Method, sample, equipment, operating conditions and units.
- Comparison baseline and uncertainty.
- Conflicts, exclusions, bias, funding or vendor involvement.
- Rights, licence, privacy, consent and publication constraints.
- Review status, reviewer/date and next verification.

For quantitative claims, include numerator, denominator, geography, reference period, unit, population definition and whether the figure is observed, estimated, modelled, provisional or forecast.

## 3. Cross-project standards and reference documents

The following are high-value entry points, not blanket declarations of compliance. Obtain and review the full normative text where a decision depends on exact clauses; ISO standards may require purchase.

| Area | Reference | Application and boundary |
|---|---|---|
| Software/product quality | [ISO/IEC 25010:2023](https://www.iso.org/standard/78176.html) | Quality model for ICT/software products; use to structure requirements and evaluation, not as a certification claim |
| Human-centred design | [ISO 9241-210:2019](https://www.iso.org/standard/77520.html) | Lifecycle principles for human-centred interactive systems; confirmed current in 2025 |
| Information security management | [ISO/IEC 27001:2022](https://www.iso.org/standard/27001) | Organisational ISMS requirements; useful risk-management reference, not a claim that a small repository is certified |
| Secure software development | [NIST SP 800-218 SSDF 1.1](https://csrc.nist.gov/pubs/sp/800/218/final) | Secure development practices across lifecycle; map practical controls to code, review, dependency and release processes |
| Supply-chain provenance | [SLSA v1.2](https://slsa.dev/spec/v1.2/) and [Build Provenance](https://slsa.dev/spec/v1.2/build-provenance) | Describes where, when and how artefacts were built; assess attainable level and actual attestation rather than claiming a level from CI alone |
| Software component metadata | [ISO/IEC 5962:2021 / SPDX 2.2.1](https://www.iso.org/standard/81870.html) | Structured package/file/snippet and licence metadata; use to improve licence and component provenance |
| Reproducible builds | [Reproducible Builds documentation](https://reproducible-builds.org/docs/) and [SOURCE_DATE_EPOCH](https://reproducible-builds.org/docs/source-date-epoch/) | Deterministic build practices, build-environment capture and independent verification |
| Web accessibility | [WCAG 2.2](https://www.w3.org/TR/wcag/) and [ISO/IEC 40500:2025 notice](https://www.w3.org/WAI/news/2025-10-21/wcag22-iso/) | Normative accessibility success criteria for the public website; test actual pages and interaction states |
| XR interoperability | [Khronos OpenXR Registry](https://registry.khronos.org/OpenXR/) | API specifications, reference pages and conformance test resources; API support does not prove target device/runtime support |
| Data stewardship | [FAIR Guiding Principles](https://www.nature.com/articles/sdata201618) | Findability, accessibility, interoperability and reuse; does not itself resolve authority or consent |
| Indigenous data governance | [CARE Principles, 2020](https://doi.org/10.5334/dsj-2020-043) | Collective Benefit, Authority to Control, Responsibility and Ethics; complement FAIR rather than treating openness as automatic permission |
| Intangible cultural heritage | [UNESCO 2003 Convention](https://www.unesco.org/en/legal-affairs/convention-safeguarding-intangible-cultural-heritage) and [Ethical Principles](https://ich.unesco.org/en/ethics-and-ich-00866) | Community primacy, respect, collaboration and free, prior, sustained and informed consent; adapt with community authority and applicable law |

### Interpretation rule

Standards are not interchangeable. A management-system standard, product-quality model, API specification, accessibility standard, legal requirement, professional guideline and research-ethics framework have different scopes and legal force. Record the edition and jurisdiction. Do not write “compliant” without a clause-level assessment and test evidence.

## 4. Kenya and East Africa: evidence that changes design

### 4.1 Digital access and communications

The Communications Authority of Kenya publishes quarterly operator-return statistics and explicitly notes that the figures depend on provider submissions. Its Q3 FY2025/26 report covers 1 January–31 March 2026.

The report records:
- 84.1 million active mobile SIM subscriptions and 157.7% mobile penetration at quarter end.
- 96.5% of active mobile subscriptions were prepaid.
- 62.6 million mobile data subscriptions, of which 84.4% were mobile broadband.
- 50.2 million smartphones and 28.5 million feature phones in the reported device counts; smartphones represented 63.7% of total mobile phones.

**Do not interpret SIM penetration as the percentage of people with phones.** Multiple SIMs, active-subscription definitions and device counts are different measures. These national aggregates do not describe Eldoret household access, affordability, coverage quality or an individual customer's device.

**Design implications to test, not assume:** low-bandwidth and offline-capable workflows; small downloads; graceful interruption/recovery; prepaid data-cost sensitivity; compatibility with lower-capability devices; and a no-account path for basic public information.

Primary source: [CA Q3 FY2025/26 Sector Statistics Report](https://ca.go.ke/sites/default/files/2026-06/Sector%20Statistics%20Report%20Quarter%203%20%20FY%202025-2026.pdf). The [CA statistics index](https://ca.go.ke/statistics) is the update point for subsequent quarters.

### 4.2 Employment and enterprise context

KNBS Economic Survey 2026 reports 21.6 million recorded jobs in 2025, with the informal sector estimated at 18.1 million. It reports 822,100 new jobs in 2025 and states that 87.2% were in the informal sector. Its employment series excludes rural small-scale agriculture and pastoral activities; the informal-sector figure is an estimate.

Uasin Gishu's 2025 County Review Report records county-reported support including 588 MSMEs funded KES 55.5 million through Inua Biashara, 118 MSMEs financed KES 7.5 million through a partnership, and capacity building for more than 4,000 MSMEs. These are county programme outputs as reported in the review, not independent impact estimates or proof of business survival/productivity gains.

Use these sources to frame research questions about informal enterprise, record keeping, digital service design, access to markets and practical support. Do not infer the size, income, demand or profitability of the loc-care market from national employment statistics.

Sources:
- [KNBS Economic Survey 2026](https://www.knbs.or.ke/wp-content/uploads/2026/04/2026-Economic-Survey.pdf)
- [Uasin Gishu County Review Report 2025](https://nepadaprmkenya.go.ke/wp-content/uploads/2025/07/UASIN-GISHU-County-Review-Report-FINAL-Annual-report-2025-V2-print.pdf)
- [Uasin Gishu CIDP 2023–2027](https://repository.kippra.or.ke/items/4441f0be-b136-4021-a21c-8603f5969f54)

### 4.3 Energy and infrastructure

EPRA's 2025/26 biannual statistics report includes generation, transmission and distribution, reliability indices, pricing systems and renewable energy. Extract county- and tariff-relevant values before sizing a workstation, mirror, edge node, UPS or solar backup. National installed generation mix is not a measure of local service reliability.

Source: [EPRA Biannual Energy & Petroleum Statistics Report 2025/26](https://epra.go.ke/sites/default/files/2026-03/Biannual%20Statistics%20Report%202025-2026.pdf).

### 4.4 Policy, privacy and research governance

The Ministry of ICT's policy index lists the Kenya AI Strategy 2025–2030, Kenya Cloud Policy (2024) and 2025 implementation guidelines, a **draft** National Broadband Strategy 2025–2030, and other national policy instruments. Preserve the distinction between enacted policy, published strategy, draft strategy and implementation guidance.

The Kenya AI Strategy discusses local-language capability, local context, Indigenous knowledge and data governance. It also identifies gaps in the specific AI regulatory framework; it does not replace existing law.

The ODPC lists the Data Protection Act 2019 and 2021 General, Registration, and Complaints Handling and Enforcement Regulations. IKAI and all repositories handling identifiable participant, client, image, voice, movement or location data must assess lawful basis, purpose, minimisation, transparency, security, retention, access/deletion and any controller/processor registration duties before collection or publication.

NACOSTI's National Scientific and Ethics Review System lists the Science, Technology and Innovation Act and 2014 regulations covering research institution registration, research quality/ethics and research licensing. Before human-participant research or collection of sensitive/identifiable data, determine whether licensing and ethics review apply; do not assume a personal or open-source project is automatically exempt.

Sources:
- [Ministry of ICT policy documents](https://ict.go.ke/policy-documents)
- [Kenya AI Strategy 2025–2030](https://www.ict.go.ke/sites/default/files/2025-06/National-AI-Strategy_IMPLEMENTATION.pdf)
- [ODPC laws and regulations](https://www.odpc.go.ke/data-protection-laws-kenya/)
- [NACOSTI / NSERS guidelines and legislation](https://nsers.nacosti.go.ke/guidelines-sops/)

## 5. Research map by repository

| Repository | Research questions and material to gather | Evidence required before claims |
|---|---|---|
| **WARENA** | GNU Guix/RDE/Guile manuals and release history; GNU Hurd/Mach architecture; Linux device APIs; X11/XLibre and Wayland comparison; storage/federation/security; repairability; power and network constraints; software supply-chain standards | Exact hardware and versions; pinned channels/commits; clean rebuild logs; package coverage; independent reproduction; boot/recovery tests; power, thermal, throughput, latency and reliability measurements |
| **IKAI** | Reflective computing and HCI literature; optical coatings and mirror substrates; display/camera/sensor manuals; OpenXR and native graphics APIs; privacy and research ethics; established mirror/display installations and industrial case studies | Optical transmission/reflection/contrast/colour shift/viewing-angle measurements; ambient-light and thermal tests; capture-to-display latency/jitter; calibration; participant consent; data-flow and retention audit |
| **GENJE** | Labanotation/Kinetography Laban, Motif Description, Laban Movement Analysis and Bartenieff Fundamentals; African/Kenyan movement scholarship; motion capture and animation standards; music timing/interoperability; livecoding systems and creative-technology case studies | Notation agreement and inter-rater review; timing drift; expressive information lost in translation; provenance/rights; consent; reproducible performance conditions; no universal claims from one dance or community |
| **NAKEBUSEN** | Loc-care and natural-hair literature; dermatology guidance; hygiene and occupational safety; cosmetic ingredient/supplier documentation; Kenya and county business rules; Eldoret customer and operating context | Owner-approved service facts; product labels/SDS where relevant; cleaning and tool procedures; documented scope and referral boundaries; consented feedback; time/cost records; no invented testimonials or medical claims |
| **FELOH Corpus** | Historiography, archaeology, linguistics, oral/living knowledge, philosophy, data sovereignty, public datasets, research methods and citation standards | Claim-source matrix; chronology and geography; independent corroboration; uncertainty; oral testimony provenance; participant/community authority; rights and exact references |
| **Gallery** | Digital preservation, archival metadata, copyright, licensing, privacy, consent, Indigenous/community authority, takedown and retention practice | Asset-level creator/source/date/licence/consent/approval record; derivative lineage; release decision; no public display while rights or consent are unresolved |
| **Public website** | WCAG 2.2, mobile-first content, performance budgets, low-bandwidth delivery, accessibility testing, local-language usability and static-site security | Automated and manual tests; real browser/device matrix; keyboard/screen-reader checks; contrast and focus; reduced-motion; payload size; deployment artifact and rollback evidence |
| **dwl-guile** | Upstream dwl/wlroots/Wayland/Guile lineage, API and ABI compatibility, security advisories, build manuals and compositor benchmarks | Pinned upstream commit; documented local delta; clean build; exact dependency versions; protocol compatibility; input/display latency; crash/recovery and hardware tests |
| **home-service-dwl-guile** | Guix Home service model, Shepherd/service lifecycle, upstream module conventions, configuration evaluation and rollback | Guix revision; evaluation/build tests; activation/deactivation; idempotence; failure handling; interaction with upstream Guix Home |
| **Profile repository** | Clear navigation to authoritative research, implemented projects and live services | Links resolve; maturity labels match specialist sources; no unsupported credentials or skill claims |

Specialist research already exists and must be extended rather than copied: IKAI's REFLECTION± dossier and mirror I/O research; WARENA's camera/display/real-time I/O and networking/storage dossiers; GENJE's movement IR, notation and music interoperability studies; NAKEBUSEN's Beauty Research Dossier; and Corpus programmes for Before Africa, COMPUTE + ARTS, and knowledge sovereignty. The Corpus index is the routing point.

## 6. Benchmark protocol

No benchmark number is meaningful without its workload and environment. Each benchmark report must include:

- Research question and decision under test.
- Competing systems and why each is a fair comparator.
- Exact hardware model/revision, firmware, OS/kernel, package/channel revisions, drivers and configuration.
- Workload, dataset provenance, input size and test duration.
- Network topology, link type, signal conditions and server location where applicable.
- Power source, battery state, ambient temperature and thermal state where relevant.
- Tool versions, commands, raw logs and analysis scripts.
- At least repeated runs sufficient to show variance; report sample count and exclusions.
- Median, p95, p99, maximum and spread where latency is measured; throughput and error/loss rates where relevant.
- Energy per task or average/peak power where energy matters.
- Failure modes, recovery time and data integrity.
- Limitations, confounders and whether another person can reproduce the result.

### 6.1 WARENA systems benchmark set

Measure clean installation/build time, closure/store size, cold and warm start, CPU/RAM, storage throughput and latency, network throughput/RTT/jitter/loss, idle and workload power, thermal throttling, recovery/rollback time, and reproducibility across independent builds.

Compare Guix/RDE and alternatives on the same machine and workload. Do not use different hardware or default configurations and then attribute the entire difference to the package manager or init system.

### 6.2 IKAI optical and real-time benchmark set

Measure reflectance and transmission over visible wavelengths where equipment allows; display luminance and contrast through the optical stack; colour error; viewing-angle dependence; image distortion; ambient-light effects; thermal behaviour; camera exposure/noise; calibration drift; and end-to-end input-to-display latency/jitter.

Keep optical feasibility, camera performance, display quality, compute throughput, synchronization and interaction quality as separate test dimensions. A mirror is not a camera, a display is not reflection, and a sensor is not a validated interpretation of a person.

### 6.3 GENJE movement and media benchmark set

Compare existing notation and motion representations on the same consented movement material. Measure time alignment, spatial/kinematic reconstruction error where ground truth exists, inter-rater agreement, notation effort, editability, interoperability and expressive/cultural information loss. Evaluate live audio/video/control timing with clock source, buffer size, drift, jitter and dropout.

Do not reduce a culturally situated dance to a universal correctness score. Technical metrics must be paired with performer, choreographer and community review under agreed terms.

### 6.4 NAKEBUSEN service and operating evidence

Track only operationally useful, proportionate records: service duration bands, material consumption, rework/maintenance, appointment/enquiry conversion if voluntarily and lawfully recorded, repeat requests, customer-reported comfort, and operating costs. Define the denominator and collection period. Avoid collecting unnecessary sensitive information; never publish client images or testimonials without explicit permission.

### 6.5 Website and supporting software

Use WCAG 2.2 as the accessibility test baseline. For the website, test real devices and browser versions, payload and image sizes, offline/slow-network behaviour, navigation, language switching, keyboard focus, contrast, reduced motion and recovery after failed loads. For compositor/service forks, test buildability, protocol compatibility, lifecycle correctness and rollback against pinned upstream revisions.

## 7. Case-study method

Select case studies because they illuminate a specific decision, not because they are famous.

For each case, record:
- Organisation, location, date and system version.
- Problem and operating context.
- Architecture and dependencies.
- Procurement and lifecycle cost where available.
- Connectivity, power, climate, staffing and maintenance context.
- Governance, rights, privacy and consent.
- Measured outcomes and source of measurements.
- Failure, discontinuation and lessons.
- Transferability to Eldoret/Kenya: what is comparable, what differs, and what must be retested.

Priority case-study pools:
- Guix deployments, reproducible distribution builds and independent build verification.
- Community networks, offline-first public services and locally maintained compute.
- Linux/X11 and native graphics/capture/display pipelines.
- Museums, performance archives and community-governed digital heritage.
- Movement notation and documentation projects led with the practitioners represented.
- Small service businesses using low-cost, locally maintainable digital workflows.
- Mirror/display installations and assistive or reflective interfaces with documented safety and privacy practices.

A vendor success story, press release or institutional target must be labelled as such. Do not convert projected benefits into measured outcomes.

## 8. Local solution design constraints

For Kenya and East Africa, every technical or service proposal should explicitly investigate:

- **Connectivity:** prepaid data costs, variable coverage, network congestion, outages, low-bandwidth and offline operation.
- **Power:** grid reliability, tariffs, backup cost, battery replacement, solar suitability and safe electrical installation.
- **Hardware:** local availability, import cost, repairability, spare parts, warranty, heat/dust exposure and component substitution.
- **People and language:** English/Kiswahili/Sheng and context-specific language needs; digital literacy; accessibility; user control; avoid assuming one language or practice represents all communities.
- **Economics:** total cost of ownership in KES; upfront and recurring costs; labour time; payment methods; informal and micro-enterprise realities.
- **Governance:** Kenya law, county requirements, data protection, research licensing, copyright, community rights and procurement terms.
- **Maintenance:** who can repair it locally, documentation quality, parts lead time, backup/restore and safe end-of-life disposal.

A local solution is not simply a global product with a local label. It is a tested adaptation whose constraints, trade-offs and maintenance path are explicit.

## 9. Priority research sequence

### Phase A — Source and claim reconciliation
1. Read existing specialist dossiers before creating new ones.
2. Check each external citation at the exact cited page/version.
3. Record primary sources, source dates, claims and limitations in the Source Register.
4. Mark stale links, inaccessible full texts, paywalled standards and unverified claims.
5. Map each source to a specific research question and decision.

### Phase B — Local evidence
1. Extract CA, KNBS, EPRA and Uasin Gishu data with table numbers and reference periods.
2. Separate national statistics from county data and founder/field observations.
3. Identify missing Eldoret-level evidence rather than interpolating national averages.
4. Conduct participant/customer research only with appropriate consent, privacy and ethics checks.

### Phase C — Comparative case studies and benchmarks
1. Define fair comparison sets and fixed test environments.
2. Reuse existing tools, protocols and upstream implementations.
3. Publish raw data and scripts when lawful and safe.
4. Record negative results and uncertainty.
5. Seek independent reproduction before strong performance claims.

### Phase D — Implementation and public claims
1. Convert validated findings into decisions, requirements or runbooks.
2. Implement only in the repository that owns the capability.
3. Pin versions and preserve upstream attribution/licence.
4. Test installation, operation, recovery and maintenance.
5. Update public copy only after evidence and owner approval.

## 10. Immediate research gaps

- **WARENA:** establish a hardware-pinned baseline on the target workstation; verify Guix/RDE package and channel state; benchmark storage, power, graphics and recovery before comparing architectures.
- **IKAI:** obtain candidate mirror/display/camera component datasheets; build an optical test matrix; identify available measurement equipment and safety constraints before selecting material.
- **GENJE:** verify primary teaching sources and notation manuals; review the existing movement IR against real practitioner workflows; define a consented pilot corpus only after rights and community authority are clear.
- **NAKEBUSEN:** verify county-level premises, public-health and occupational-safety requirements with the relevant authorities; compile product labels/SDS and cleaning procedures; collect only proportionate operating evidence.
- **FELOH Corpus:** reconcile existing bibliographies and historical materials, remove duplicate source entries carefully, and add exact claim-to-page references.
- **Gallery:** keep approval gates closed until each asset has complete provenance and publication rights.
- **Website:** complete actual browser/device QA; a successful deployment workflow alone is not visual verification.
- **Supporting forks:** perform pinned upstream comparison and clean build/lifecycle tests.

## 11. Research status

This document is a programme map and first source-grounded intake. It is **not** a completed systematic review, legal opinion, market study, product certification, benchmark report, field study or independent implementation audit. The source entries in [source-register.md](source-register.md) and existing specialist dossiers carry the detailed source-level review status.

**Rule:** Research until the question is bounded; measure before claiming; reuse before inventing; adapt with local evidence; preserve the authority of the people and communities represented.
