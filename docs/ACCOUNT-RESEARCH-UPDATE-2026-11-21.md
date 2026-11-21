# GitHub Account Research and Maintenance Update — 2026-11-21

**Account:** @donfelohke  
**Canonical repository:** feloh-corpus  
**Status:** DOCUMENTATION UPDATE / LIVE REPOSITORY SNAPSHOT  
**Scope:** All ten public repositories accessible through the connected GitHub account.

## 1. Account inventory

The account currently exposes ten public, unarchived repositories, all with `main` as the default branch:

1. `donfelohke.github.io` — public website
2. `feloh-corpus` — shared canon, governance and evidence
3. `WARENA` — CAPABILITY systems and infrastructure
4. `Genje` — EXPRESSION creative and embodied practice
5. `Ikai` — MIRROR reflective-computing research
6. `NAKEBUSEN` — ROOT commercial practice
7. `Gallery` — asset provenance and rights
8. `donfelohke` — public author profile
9. `dwl-guile` — WARENA-maintained upstream fork
10. `home-service-dwl-guile` — WARENA-maintained Guix Home service fork

A fresh account-scoped open-PR search returned no open pull requests authored in or belonging to these ten repositories at the time of this review. This is a point-in-time result, not a guarantee that no external contribution or new PR will appear later.

## 2. Canonical domain map

| Domain | Responsibility | Current maturity boundary |
|---|---|---|
| NAKEBUSEN · ROOT | Loc care, beauty craft, livelihood and the only commercial transaction interface | Existing business and public catalogue; individual compliance/operational facts require their own evidence |
| IKAI · MIRROR | Reflective environments, optics, sensing, memory and interaction | RESEARCH; portal source/build exists; public Pages deployment remains blocked |
| GENJE · EXPRESSION | Genge, music, livecoding, movement and choreography | Creative practice and RESEARCH; no integrated motion platform claimed |
| WARENA · CAPABILITY | GNU/Linux, Guix, embedded systems, networks, energy and infrastructure | Documentation/research; host and field deployments require test evidence |
| FELOH Corpus | Shared canon, provenance, governance and research records | SOURCE OF RECORD |

F3L0H is the human authorship identity, not a fifth domain. GENJE NODE remains nested under WARENA. Gallery, website, profile and the two supporting forks are repository roles, not additional domains.

**Commercial boundary:** ONLY NAKEBUSEN TRANSACTS.

## 3. New specialist research documents

This maintenance batch adds two specialist reports and links them into the owning knowledge bases:

- WARENA — [Sovereign Movement Systems Research](https://github.com/donfelohke/WARENA/blob/main/docs/research/SOVEREIGN-MOVEMENT-SYSTEMS-RESEARCH-2026-11-21.md): EV software and embedded systems, CAN, charging, open SDK/toolchain landscape, matatu/nduthi operating context, portable power, off-grid energy, Kenyan policy, battery lifecycle and safety gates.
- NAKEBUSEN — [ROOT Operations, Tax and Data-Protection Research](https://github.com/donfelohke/NAKEBUSEN/blob/main/docs/ROOT-OPERATIONS-AND-COMPLIANCE-RESEARCH-2026-11-21.md): KRA eTIMS, ODPC registration applicability, customer data controls, county verification, service-quality evidence and commercial boundaries.

Existing specialist reports remain authoritative for their subjects:

- IKAI — [REFLECTION±: Light In, Light Out, Compute](https://github.com/donfelohke/Ikai/blob/main/docs/REFLECTION-PLUS-MINUS-LIGHT-IN-LIGHT-OUT-COMPUTE-RESEARCH-2026-11-21.md) and [M1 Engineering Validation](https://github.com/donfelohke/Ikai/blob/main/docs/IKAI-MIRROR-M1-ENGINEERING-VALIDATION-2026-11-18.md).
- GENJE — [Movement IR and Motion Research](https://github.com/donfelohke/Genje/blob/main/docs/GENJE-MOVEMENT-IR-AND-MOTION-RESEARCH-2026-11-20.md) and [Movement–Music Interoperability Study](https://github.com/donfelohke/Genje/blob/main/docs/GENJE-MOVEMENT-MUSIC-INTEROPERABILITY-STUDY-2026-11-20.md).
- FELOH Corpus — [F3L0H Master Research Dossier](./F3L0H-MASTER-RESEARCH-DOSSIER-2026-11-21.md).

## 4. Workflow snapshot observed on 21 November 2026

| Repository | Latest sampled main workflow result | Interpretation |
|---|---|---|
| Website | Static HTML checks: success; website quality/build: success | Browser quality and artifact build passed in the sampled run; this is not a complete live-site or content audit |
| FELOH Corpus | Documentation validation: success | Documentation checks passed; this is not claim-by-claim scholarly validation |
| WARENA | Repository baseline validation: success | Required documentation checks passed; no Guix host build or runtime validation implied |
| GENJE | Repository baseline validation: success | Documentation baseline passed; no motion-capture or performance implementation implied |
| IKAI | Validation: success; Jekyll build/artifact: success; deploy: failure | Source and build passed, but the Pages deployment job failed |
| NAKEBUSEN | Repository baseline validation: success | Required documentation baseline passed; no live booking/payment end-to-end test implied |
| Gallery | Governance baseline validation: success | Governance checks passed; no asset rights or consent approval inferred |
| Profile | No recent workflow run sampled | Readme/profile content review only |
| dwl-guile | No recent workflow run sampled | Fork build and runtime remain unverified |
| home-service-dwl-guile | No recent workflow run sampled | Guix Home service build and lifecycle remain unverified |

The IKAI deployment failure is the only sampled main workflow failure in this set. The validate and build jobs passed; the deploy job failed. The previous repository audit recorded GitHub Pages as not enabled. The current connector does not expose a Pages configuration write operation, so this batch does not attempt to change repository hosting settings. The owner must enable/configure Pages in GitHub repository settings before a deployment retry can be meaningful.

## 5. Maintenance changes in this batch

- Added a WARENA research dossier for Sovereign Movement Systems.
- Added a NAKEBUSEN operations and compliance research note.
- Linked both reports from their owning repository indexes.
- Added the reports to the FELOH Corpus master research dossier and documentation index.
- Added current research pointers to the author profile repository.
- Kept specialist material in its owning repository; the Corpus links rather than duplicating full reports.

The following repositories receive no file changes in this batch because their current material already reflects the relevant research or governance boundary and no new correction was evidenced: IKAI, GENJE, Gallery, public website, dwl-guile and home-service-dwl-guile. This is a scoped decision, not a claim that their contents have been exhaustively re-audited.

## 6. Scope and non-claims

This batch is documentation and index maintenance. It does not:

- change the public website's deployed pages or customer-facing service copy;
- change NAKEBUSEN prices, services, payment details or booking terms;
- create new repositories or mutate upstream repositories;
- alter Git history, force-push, delete branches or bypass review;
- enable GitHub Pages or modify account/repository security settings;
- procure, install or modify vehicles, chargers, batteries, solar equipment or mirror hardware;
- claim a working IKAI mirror, GENJE motion system, EV platform, microgrid, Guix workstation or production deployment.

A passing documentation workflow is evidence only for the checks that workflow runs. A commit is not deployment evidence. A source repository is not a validated hardware system.

## 7. Follow-up gates

1. Enable/configure GitHub Pages for IKAI, then rerun the deployment workflow and verify the public URL.
2. Verify repository rulesets and required review/status-check policies with the appropriate GitHub administration interface.
3. Continue claim-level bibliography and source review in the Corpus.
4. Build and test the WARENA virtual CAN/embedded research bench before any physical vehicle experiment.
5. Measure IKAI optical and input/output behaviour against the M1 validation specification.
6. Validate GENJE movement representations with practitioners and consented, context-rich examples.
7. Verify NAKEBUSEN's actual eTIMS, ODPC and Uasin Gishu County position against owner-held records and current official guidance.

**Governance rule:** inventory is not validation; documentation is not implementation; implementation is not release; release is not field proof.
