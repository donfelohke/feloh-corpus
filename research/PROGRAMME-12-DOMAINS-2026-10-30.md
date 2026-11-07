# FELOH Research Programme — Twelve Domains

**Programme date:** 2026-10-30  
**Status:** RESEARCH PROGRAMME / SOURCE-DISCOVERY BASELINE  
**Canonical home:** `donfelohke/feloh-corpus`  
**Specialist work:** NAKEBUSEN · WARENA · IKAI · GENJE  
**Principle:** ONE CORPUS → MANY VIEWS → ONE PRACTICE.

This document converts the FELOH research areas into an executable, evidence-led programme. It is an index and work plan, not a claim that every subject has been researched, every source read in full, or every project implemented.

## 1. Research domains

| ID | Domain | Core questions | Specialist home |
|---|---|---|---|
| R01 | African history, identity and civilisation | How have African societies, states, intellectual traditions and regional identities changed across time? How did Roman provincial rule shape one North African regional category without creating Africa or the continent? | Corpus |
| R02 | African philosophy, politics and political economy | How are knowledge, personhood, power, justice, sovereignty, land, labour and self-determination theorised and practised? | Corpus |
| R03 | Sovereign computing and operating systems | Which GNU/Linux, Guix, RDE, Guile, desktop, storage and networking components can be reproduced, maintained and recovered locally? | WARENA |
| R04 | AI and distributed intelligence | What can local inference, federated learning and agent systems do under explicit privacy, provenance, evaluation and human-authorization constraints? | WARENA / IKAI |
| R05 | Distributed systems and internet infrastructure | How should Git, ActivityPub, Fediverse services, peer-to-peer networking, offline-first storage and federation be evaluated for operational sovereignty? | WARENA |
| R06 | Telecommunications and financial infrastructure | How do USSD, operator access, M-Pesa/Daraja, bank rails, interoperability and regulation fit together in a Kenya-first service workflow? | WARENA / NAKEBUSEN |
| R07 | Computational movement and embodied intelligence | How can Laban/Bartenieff movement concepts, notation and observation inform creative computation without turning people into scores or covert profiles? | IKAI / GENJE |
| R08 | Music, culture and computational art | How do Genge, live coding, algorithmic composition and generative visuals support authored, attributable cultural practice? | GENJE |
| R09 | Enterprise, entrepreneurship and market research | What customer needs, service economics, local demand and delivery constraints can be evidenced for NAKEBUSEN LOCS and DIGITAL? | NAKEBUSEN |
| R10 | Design, architecture and digital experience | Does the public experience communicate the offer clearly and work across devices, languages, assistive technologies and real enquiry journeys? | NAKEBUSEN / Website |
| R11 | Human development, education and knowledge systems | How can self-directed learning, apprenticeship, reflective practice, local knowledge stewardship and durable research records support human agency? | Corpus / IKAI |
| R12 | Science, mathematics and engineering | Which mathematical, scientific and systems-engineering methods improve modelling, experimentation, verification and reproducibility across the programme? | WARENA / IKAI / GENJE |

### Domain boundaries

- FELOH is the human author and integrated practice.
- NAKEBUSEN is the sole commercial and customer-transaction interface; LOCS and DIGITAL are its public service paths.
- WARENA is the systems-engineering and infrastructure practice powering NAKEBUSEN DIGITAL.
- IKAI is reflective-computing research, not a released product, clinical tool, scoring system or surveillance system.
- GENJE / GENJE ZA WARENA is cultural and creative practice, not a checkout brand.
- The Corpus owns shared terminology, source provenance, evidence standards and cross-domain indexes. Specialist repositories own their domain records and implementation details.

## 2. First execution queue

The first ten work packages translate the priority tracks into repository work. This is an ordering for research, not a ranking of intellectual importance.

| Order | Work package | Primary output | Current repository evidence |
|---|---|---|---|
| 01 | GNU Guix / RDE / DWL-Guile | Pinned source audit, reuse/adapt/reject/test decisions, build and runtime qualification plan | WARENA PR #12 |
| 02 | Sovereign AI infrastructure | Flower/Ollama architecture comparison, local/federated threat model, human-review gates | Corpus PR #19; WARENA/IKAI follow-up |
| 03 | USSD and Kenyan payment rails | Operator/payment/network separation, integration feasibility and regulatory questions | WARENA PR #13 |
| 04 | African historical identity | Source-led chronology, regional terminology and contested-claim register | Corpus PR #15; programme source queue |
| 05 | IKAI Reflective Computing | Research questions, ethics, privacy model and reproducibility protocols | IKAI PR #5 |
| 06 | Computational movement | Laban/Bartenieff resource map, terminology, method comparison and consent-aware study design | Corpus Laban resource map; IKAI / GENJE |
| 07 | Fediverse and distributed publishing | ActivityPub/Git/Pubstrate/Mastodon architecture and threat-model comparison | WARENA Guile ecosystem PR #14 |
| 08 | NAKEBUSEN market intelligence | Customer segments, local evidence, competitor observation protocol, service economics | Corpus PR #14 and #15; NAKEBUSEN PR #6 |
| 09 | Agentic OS architecture | Agent authority model, desktop integration, reproducibility and human authorization | WARENA PR #12 and desktop architecture |
| 10 | Genge computational culture | Attributable works, live-coding toolchain, movement/music research and release provenance | Corpus PR #13; GENJE repository |

The remaining domains R10–R12 are cross-cutting gates: design/accessibility for all public interfaces, learning and knowledge stewardship for all research, and scientific/reproducibility methods for all technical claims.

## 3. Source-discovery starter set

These are initial institutional, standards, project or primary-source entry points. A link is a discovery lead, not proof that the full source has been read or that every claim is supported.

### R01 — African history and civilisation
- UNESCO, [General History of Africa](https://www.unesco.org/en/general-history-africa): continent-wide scholarly series, historiography and regional histories. Review individual volumes and bibliographies; do not flatten distinct regions or periods.
- David Stone, [Roman Africa, Oxford Bibliographies](https://academic.oup.com/reference/62365/reference-article-abstract/554612621): specialist entry point for Roman-period North Africa. Its use of “Africa” is a Roman-period regional category, not the origin of the continent or all African identities.

### R02 — African philosophy and political thought
- [Stanford Encyclopedia of Philosophy: African Sage Philosophy](https://plato.stanford.edu/entries/african-sage/): overview of Henry Odera Oruka’s project, its aims and debates. Read Oruka’s primary texts and critical responses before adopting a simplified account.

### R03 — Sovereign computing
- [GNU Guix Manual](https://guix.gnu.org/manual/): primary technical reference; pin manual version and Guix revision for implementation claims.
- [Reproducible Builds — Definition](https://reproducible-builds.org/docs/definition/): operational definition; a project must still demonstrate reproducibility for a named artefact and pinned inputs.
- [GNU Guile Manual](https://www.gnu.org/software/guile/manual/guile.html): language/runtime reference; distinguish upstream Guile capability from WARENA integration.

### R04 — AI and distributed intelligence
- [Flower Framework documentation](https://flower.ai/docs/framework/): federated-learning framework, tutorials, strategies, privacy-related mechanisms and deployment architecture. Framework features do not by themselves prove privacy or suitability for a particular deployment.
- [Ollama documentation](https://docs.ollama.com/): local model runtime and API reference. Validate hardware, model licence, resource use, network exposure and data handling independently.

### R05 — Distributed systems and internet infrastructure
- [W3C ActivityPub Recommendation](https://www.w3.org/TR/activitypub/): protocol specification; distinguish protocol conformance from the behaviour and security of a particular server.
- [Pro Git book](https://git-scm.com/book/en/v2): Git object model and collaboration reference; supplement with current Git documentation and repository-specific tests.
- [Pubstrate source repository](https://github.com/spritely/pubstrate): inspect source revision, dependencies, licence, maturity and protocol boundaries before proposing reuse.

### R06 — Telecommunications and financial infrastructure
- [Safaricom Daraja developer portal](https://developer.safaricom.co.ke/): official M-PESA API onboarding and sandbox entry point; production onboarding and permissions are separate prerequisites.
- [Central Bank of Kenya](https://www.centralbank.go.ke/): primary regulator source for payment-system legislation, oversight and official notices. Verify the current instruments and seek qualified Kenyan legal advice before regulated activity.
- [GSMA](https://www.gsma.com/): industry research and standards context for mobile operators and mobile money; distinguish industry publications from Kenyan operator-specific commitments.

### R07 — Computational movement
- [Laban/Bartenieff and Somatic Studies International: Movement Analysis](https://labaninternational.org/scope-of-practice/movement-analysis/): institutional orientation to LMA/LBMS and its Body, Effort, Shape and Space dimensions. Follow references to original scholarship and preserve the distinction between observation and interpretation.

### R08 — Music and computational art
- [TidalCycles documentation](https://tidalcycles.org/docs/): live-coding environment and learning materials; record version and reproducible examples.
- [SuperCollider documentation](https://doc.sccode.org/): language and synthesis server reference; test patches and environment-specific behaviour.
- [Hydra](https://hydra.ojack.xyz/): browser-based live-coding visuals; assess licence, browser requirements and performance for each use.

### R09 — Enterprise and market research
- [KNBS Economic Survey 2026](https://www.knbs.or.ke/reports/2026-economic-survey/): national economic and sector context. Cite exact table, period, unit and definition; national data is not an Eldoret market-size estimate.
- [KNBS 2026 Integrated Labour Force Survey](https://www.knbs.or.ke/2026-kenya-integrated-labour-force-survey-ilfs/): labour-market and informal/digital employment survey context. Extract only statistics with relevant geographic and population coverage.
- Local competitor prices, customer sentiment, willingness to pay and conversion remain field-verification tasks; do not infer them from national statistics or unverified social posts.

### R10 — Design and digital experience
- [W3C WCAG 2.2](https://www.w3.org/TR/wcag/): normative accessibility success criteria. Automated scans alone cannot establish conformance; test the complete page and interactions with human evaluation.
- [web.dev Core Web Vitals](https://web.dev/articles/vitals): performance measurement orientation. Field data, lab results and source-level assumptions must be reported separately.

### R11 — Learning and knowledge stewardship
- [CARE Principles for Indigenous Data Governance](https://www.gida-global.org/care): collective benefit, authority to control, responsibility and ethics. Apply with community context and consent; do not treat a principles page as community authorization.
- [FAIR Principles](https://www.go-fair.org/fair-principles/): findability, accessibility, interoperability and reuse for research data. FAIR does not override privacy, consent, Indigenous governance or rights restrictions.

### R12 — Science, mathematics and systems engineering
- [NASA Systems Engineering Handbook](https://www.nasa.gov/reference/systems-engineering-handbook/): lifecycle, system design, product realization and technical management reference. Tailor methods to project scale; NASA practice is a reference, not a mandatory WARENA process.

## 4. Evidence and research workflow

Every substantive research record must contain:

1. A bounded research question and scope.
2. A dated search log and source register.
3. Source type, author/institution, version/date and access date.
4. Exact passage, page, table, commit or reproducible observation supporting each claim.
5. Separate labels for verified source statements, corroborated findings, disputed claims, interpretations, hypotheses, opinions and proposals.
6. Counter-evidence, source limitations, uncertainty and unresolved questions.
7. A recommendation with explicit assumptions and a verification plan.
8. A specialist repository destination and a cross-link back to this Corpus.

### Maturity vocabulary

Use `LIVE`, `PROTOTYPE`, `RESEARCH`, `CONCEPT`, `HISTORICAL`, `SUPERSEDED` or `UNKNOWN`. A README, design, PR, upstream release or successful static test does not establish deployment, production readiness, legal compliance or customer outcomes.

### Human and community safeguards

- AI may assist discovery, comparison and drafting; a human reviews sources, claims and decisions.
- Do not publish private conversations, customer records, credentials, precise personal location, or identifiable participant data.
- Community knowledge requires provenance, consent, attribution, context and appropriate authority to share.
- Do not turn IKAI or movement research into biometric identification, diagnosis, ranking, hidden profiling or surveillance.
- Commercial customer enquiries and transactions remain with NAKEBUSEN only.

## 5. Existing work — avoid duplication

The following open work already provides foundations and should be reviewed/reconciled before creating parallel documents:

| Repository | Existing work | Treatment |
|---|---|---|
| [feloh-corpus](https://github.com/donfelohke/feloh-corpus) | PR #19 cross-domain sources/claims/learning paths; PR #15 heritage and NAKEBUSEN research; PR #14 Eldoret informal-economy baseline; PR #13 COMPUTE + ARTS | Extend the current cross-domain branch; reconcile source IDs and claim IDs before merging |
| [WARENA](https://github.com/donfelohke/WARENA) | PR #12 RDE/DWL-Guile; PR #13 USSD/Taler/GNUnet; PR #14 GNU Guile ecosystem | Keep research status; do not infer package compatibility or production readiness |
| [NAKEBUSEN](https://github.com/donfelohke/NAKEBUSEN) | PR #6 similar-projects benchmark framework | Complete dated local verification; do not invent competitor prices or customer sentiment |
| [IKAI](https://github.com/donfelohke/Ikai) | PR #5 MIRROR science and technology research base | Preserve privacy/ethics boundaries and research-only maturity |
| [Website](https://github.com/donfelohke/donfelohke.github.io) | PR #101 integration candidate; PR #99/#100 are overlapping predecessors | Review #101 as the consolidation candidate; do not merge predecessors independently |
| [GENJE](https://github.com/donfelohke/Genje) | Creative-practice README, governance and language notes | Add source-backed studies only where a distinct gap is demonstrated |

PR status is a repository snapshot and must be refreshed before a merge or release decision. This programme document does not merge, close or supersede any PR.

## 6. Next verification gates

- [ ] Confirm all current PR heads, changed-file lists, review threads and CI results.
- [ ] Reconcile the Corpus PR #19 branch with the current master topic register and existing source/claim IDs.
- [ ] Review the full text of priority primary sources rather than relying on landing-page summaries.
- [ ] Pin upstream revisions and licenses before technical reuse recommendations become implementation decisions.
- [ ] Extract exact KNBS tables and establish a local Eldoret fieldwork protocol before estimating local demand.
- [ ] Validate public website changes with static tests, browser tests, keyboard/accessibility review and release-authorized live checks.
- [ ] Keep every prototype, build, deployment, customer outcome and regulatory conclusion at UNKNOWN until directly evidenced.

**Programme rule:** research first; source-level audit second; implementation only after an explicit, scoped decision; human authorization before release.
