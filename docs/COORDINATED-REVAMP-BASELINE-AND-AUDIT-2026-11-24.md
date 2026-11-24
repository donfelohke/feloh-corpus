# Coordinated Revamp — Baseline Audit and Work Register

**Date:** 24 November 2026  
**Programme:** [Issue #78](https://github.com/donfelohke/feloh-corpus/issues/78)  
**Scope:** All ten existing public repositories, the public website and the GitHub account  
**Status:** ACTIVE — research and implementation proceed together  
**Change authority:** Founder-approved; no new repositories by default

## 1. Governing direction

Three coordinated workstreams:

1. **ALL REPOS:** improve research quality, documentation, architecture, implementation evidence, project identity, tests and cross-repository coherence.
2. **PAGE — BETTER:** research design and copy together, improve the public experience, implement and verify.
3. **ACCOUNT:** improve the profile landing experience and repository discovery; complete account-level settings manually where the GitHub integration does not expose them.

Preserve project boundaries, upstream attribution, licences, historical provenance and maturity honesty. **ONLY NAKEBUSEN TRANSACTS.**

## 2. Verified inventory

The connected GitHub account returned ten public repositories. All use `main` as the default branch; none is archived.

| Repository | Canonical responsibility | Baseline finding | Revamp focus |
|---|---|---|---|
| [donfelohke.github.io](https://github.com/donfelohke/donfelohke.github.io) | Public website | Static bilingual HTML/CSS, research links, source regression suite and existing visual standards | Design and copy research; first-screen hierarchy; mobile and accessibility; browser and deployment verification |
| [feloh-corpus](https://github.com/donfelohke/feloh-corpus) | Shared canon, governance, evidence and provenance | Strong identity architecture and source routing; some README duplication and small editorial defects remain | Consolidate navigation, cross-reference all programme research and keep one canonical source per fact |
| [NAKEBUSEN](https://github.com/donfelohke/NAKEBUSEN) | ROOT practice and sole commercial interface | Clear service catalogue, published prices, location and enquiry/payment safeguards | Index current operations research; review service journey, local evidence and public facts |
| [WARENA](https://github.com/donfelohke/WARENA) | CAPABILITY systems engineering | Strong libre-first, local-first, reproducibility and maturity principles | Index latest validation research; test traceability from research claims to runnable evidence |
| [Ikai](https://github.com/donfelohke/Ikai) | MIRROR / reflective-computing research | Research status and privacy boundaries are explicit; README naming note was more tentative than founder-provided context | Align name context and current M1 research index; maintain evidence and privacy gates |
| [Genje](https://github.com/donfelohke/Genje) | EXPRESSION creative and embodied practice | Strong cultural/contextual nuance and creative boundaries | Index latest movement notation research; strengthen provenance and interoperability trail |
| [Gallery](https://github.com/donfelohke/Gallery) | Asset rights, consent and approval | Correctly initialized as governance, not a public image gallery; no asset is automatically approved | Keep empty/proposed states honest; test rights, consent and approval records before publication |
| [donfelohke](https://github.com/donfelohke/donfelohke) | GitHub profile README | Profile README presents the five identities, selected work and latest research; selected-work order matches intended pinned hierarchy | Review short bio, public account fields, repository descriptions/topics and actual pinned repositories |
| [dwl-guile](https://github.com/donfelohke/dwl-guile) | Supporting compositor project | README identifies upstream-based WARENA support role and disclaims unsupported release claims | Verify upstream relationship, licence, build/test instructions, supported state and attribution |
| [home-service-dwl-guile](https://github.com/donfelohke/home-service-dwl-guile) | Supporting Guix Home integration | README identifies supporting integration role and WARENA research relationship | Verify package/service tests, installation examples, compatibility and upstream attribution |

This is a README and repository metadata baseline, not a complete code, dependency, security or runtime audit of every repository.

## 3. Website research records

The website repository now contains:

- [Website Revamp Research](https://github.com/donfelohke/donfelohke.github.io/blob/main/research/website-revamp-research-2026-11-24.md) — local market, brand, search and accessibility desk research.
- [Design Research & Reference Audit](https://github.com/donfelohke/donfelohke.github.io/blob/main/research/DESIGN-RESEARCH-AND-REFERENCE-AUDIT-2026-11-24.md) — task-based hierarchy, WCAG 2.2, interaction and performance criteria.
- [Copy & Content Research Audit](https://github.com/donfelohke/donfelohke.github.io/blob/main/research/COPY-AND-CONTENT-RESEARCH-AUDIT-2026-11-24.md) — content tasks, English/Kiswahili review questions, facts and editorial recommendations.
- [Ecosystem Research Integration](https://github.com/donfelohke/donfelohke.github.io/blob/main/research/ecosystem-research-integration-2026-11-24.md) — latest research links and publication scope.

These are desk-research records. They do not claim participant testing, measured conversion improvements or WCAG conformance.

## 4. Changes completed in this programme

- Website PR [#191](https://github.com/donfelohke/donfelohke.github.io/pull/191) merged: design and copy research audits.
- IKAI PR [#38](https://github.com/donfelohke/Ikai/pull/38) merged: founder-provided name meaning context and current M1 research index.
- WARENA PR [#56](https://github.com/donfelohke/WARENA/pull/56) merged: current reproducible systems research index.
- GENJE PR [#40](https://github.com/donfelohke/Genje/pull/40) merged: current movement notation research index.
- NAKEBUSEN PR [#34](https://github.com/donfelohke/NAKEBUSEN/pull/34) merged: current Eldoret operations research index.
- Website PR [#190](https://github.com/donfelohke/donfelohke.github.io/pull/190) and profile README research index update remain part of the preceding 24 November integration.

## 4A. Follow-up execution — 24 November 2026

The second implementation pass completed four additional documentation PRs:

- [GENJE PR #41](https://github.com/donfelohke/Genje/pull/41) merged: consolidated the README, removed repeated identity addenda, indexed current movement/interoperability and cooperative-media research, and made the cultural art-direction rule more context-specific. Main validation passed: [run 45338071437](https://github.com/donfelohke/Genje/actions/runs/45338071437).
- [Gallery PR #27](https://github.com/donfelohke/Gallery/pull/27) merged: consolidated governance guidance and made the initialized/pending approval state and text-first publication boundary clearer. Main validation passed: [run 45338085896](https://github.com/donfelohke/Gallery/actions/runs/45338085896). No assets were added or approved.
- [home-service-dwl-guile PR #8](https://github.com/donfelohke/home-service-dwl-guile/pull/8) merged: documented the upstream project, the Org-mode installation guide and the upstream-channel/fork boundary. Documentation-only; this repository has no Actions workflow, and no Guix build or runtime validation is claimed.
- [FELOH Corpus PR #83](https://github.com/donfelohke/feloh-corpus/pull/83) merged: corrected the remaining malformed emphasis around the canonical transaction boundary and removed a repeated copy-system paragraph. Pull-request validation passed; post-merge validation is recorded separately in Actions.

The four follow-up PRs are merged. No open PRs were returned by the account-wide open-PR query at the time of this update.

### Website publication observation

A fresh external read of https://donfelohke.github.io/ on 24 November 2026 returned the current page content, including the approved KES 700 / KES 1,500 / KES 3,500 service prices, English/Kiswahili content, WARENA's engagement-scope disclosure, the NAKEBUSEN-only transaction boundary, and the manual M-PESA safeguards. This is a current publication observation, not a substitute for manual browser, device, keyboard or screen-reader testing. Website issue [#187](https://github.com/donfelohke/donfelohke.github.io/issues/187) remains open for that work.

### IKAI Pages deployment diagnosis

The latest main-branch workflow [run 45336632509](https://github.com/donfelohke/Ikai/actions/runs/45336632509) completed validation and Jekyll build successfully but failed in the deploy job with HTTP 404. The deploy log explicitly says to ensure GitHub Pages is enabled. This is an account/repository Settings prerequisite, not a source-build failure. Pages must be enabled in repository Settings before a deploy rerun can verify publication.

## 5. Account presentation

The profile README's selected-work order already follows the intended sequence:

1. Personal website
2. NAKEBUSEN
3. WARENA
4. FELOH Corpus
5. IKAI
6. GENJE

The GitHub integration can read the connected profile and repository README, but does not expose account profile-edit, pinned-repository reorder, repository-description or topic-edit actions. Those settings require manual completion in GitHub.

## 6. Research and engineering standards

- Use the FELOH Copy System and Five-Identity Architecture as the shared identity/editorial baseline.
- Specialist repositories own their detailed research and implementation records.
- Record source, date, claim, evidence class, method, limitation and decision.
- Prefer existing standards and projects; reuse and credit creators.
- Distinguish RESEARCH, CONCEPT, PROTOTYPE, IMPLEMENTATION, VALIDATED and LIVE.
- A commit proves source history, not runtime behaviour or deployment.
- A passing automated check is not a user study or conformance certificate.
- Preserve native-first, libre-first, local-first and human-directed technology boundaries for WARENA/IKAI.

## 7. Acceptance gates

### Repositories
- Every repository has an owner, purpose, source-of-truth README, licence, contribution guidance where appropriate and accurate maturity labels.
- Research links resolve and are indexed in the owning project and Corpus.
- Code changes have reproducible build/test evidence; supporting forks retain upstream attribution.

### Page
- Visitors can identify the loc-care offer, Eldoret location, prices and enquiry path immediately.
- WARENA remains a distinct capability path; IKAI and GENJE remain clearly non-transactional.
- English and Kiswahili are reviewed in context.
- Responsive, keyboard, screen-reader, contrast, reduced-motion and performance checks are recorded.
- Live Pages deployment is checked independently from merge state.

### Account
- Profile first screen communicates human authorship and clear project hierarchy.
- Six pinned repositories follow the intended order.
- Repository descriptions/topics support discovery and do not overstate release maturity.
- Account bio and profile links are coherent with the website.

## 8. Manual completion register

| Item | Required action | Status |
|---|---|---|
| GitHub pinned repositories | Pin website, NAKEBUSEN, WARENA, FELOH Corpus, IKAI, GENJE in that order | Manual |
| GitHub bio / profile fields | Review and set concise identity, location and website link | Manual |
| Repository descriptions and topics | Review all ten descriptions/topics in repository Settings | Manual |
| Visual design exploration | Desk research is recorded in the website repository; a rendered visual exploration remains pending | Research complete / exploration pending |
| Browser/device review | External page read returns current content; manual Android/desktop, EN/SW, theme, keyboard, screen-reader and reflow checks remain | Pending manual QA |
| GitHub Pages deployment | Website page content externally observed current; IKAI Pages deploy remains blocked because Pages is not enabled | Partially verified / IKAI blocked |

## 9. Explicit limits

No claims of a finished whole-account revamp, full code audit, participant-validated redesign, translation QA, WCAG certification or live deployment should be made until the relevant evidence is recorded.
