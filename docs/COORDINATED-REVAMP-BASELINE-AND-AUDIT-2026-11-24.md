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
| Visual design exploration | Capture current page and compare visual directions in Product Design Work workflow | Pending |
| Browser/device review | Verify Android and desktop, EN/SW, theme, keyboard and reflow | Pending |
| GitHub Pages deployment | Verify latest merged website commit is live | Pending |

## 9. Explicit limits

No claims of a finished whole-account revamp, full code audit, participant-validated redesign, translation QA, WCAG certification or live deployment should be made until the relevant evidence is recorded.
