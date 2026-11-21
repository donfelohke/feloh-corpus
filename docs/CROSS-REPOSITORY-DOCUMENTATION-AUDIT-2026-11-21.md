# Cross-repository documentation audit — 2026-11-21

**Scope:** ten public repositories under `donfelohke`, default branch `main`.  
**Purpose:** record the documentation state visible in the account-wide review and identify evidence-backed next actions.  
**Method:** inspect repository inventory, the six previously unupdated README entry points, their dated upgrade plans where present, the two fork READMEs, the Corpus README and account-wide open-PR search. This is a documentation-entry-point audit, not a full recursive source, link, binary, build or deployment audit.

## Executive finding

The ten-repository ecosystem has substantial documentation, but it is **not yet possible to certify every repository as fully documented or operationally verified**. Six repositories not included in the immediately preceding documentation batch already have meaningful README documentation and dated upgrade plans or maintenance records. The outstanding work is specific validation and evidence closure, not wholesale documentation replacement.

The account-wide open pull-request search returned **zero open PRs** at the time of this review. There was therefore no existing open PR queue to merge into `main`.

## Repository register and review findings

| Repository | Documentation entry point reviewed | Evidence-backed remaining work |
|---|---|---|
| `feloh-corpus` | `README.md`, repository-wide baseline and account-update records | Import and reconcile the complete F3L0H-PRESENT-001 source edition and full folder tree; retain the distinction between constitutional spine and verbatim corpus transcription; continue source, claim and cross-link verification. |
| `WARENA` | Prior batch: README, knowledge-base index and sovereign movement research | Validate architecture against actual source and build evidence; record exact upstream revisions, reproducible build results and tested operational states. Research records must remain labelled as research until tested. |
| `NAKEBUSEN` | Prior batch: README, knowledge-base index and ROOT operations/compliance research | Complete owner-held operational and county-permit evidence checks; verify applicable tax and data-protection obligations against current primary sources and actual business circumstances. Do not publish private customer records. |
| `Ikai` | `README.md`, `docs/REPOSITORY-UPGRADE-PLAN-2026-11-21.md` | The plan records a GitHub Pages deployment failure because Pages was not enabled. Owner action is required in repository Settings → Pages → Build and deployment → GitHub Actions, followed by a successful deployment and live URL check. Also complete portal link/navigation audit and M1 optical / bidirectional-IO validation protocol. No live portal or physical prototype is claimed. |
| `Genje` | `README.md`, `docs/REPOSITORY-UPGRADE-PLAN-2026-11-21.md` | Build a sourced register for language, music and movement references; establish a consistent creative-work record; select one bounded, testable livecoding/movement study. Preserve attributed artist interpretation versus general linguistic evidence, and record rights, consent and actual performance status. |
| `donfelohke.github.io` | `README.md`, `docs/REPOSITORY-UPGRADE-PLAN-2026-11-21.md` | Complete source and browser audit, mobile/desktop accessibility review, responsive screenshots, link/language-control checks and deployment smoke test. A green workflow is not proof of a live deployment. No production website change is made by this audit. |
| `Gallery` | `README.md`, `docs/REPOSITORY-UPGRADE-PLAN-2026-11-21.md` | Reconcile the asset manifest against committed original binaries; resolve the supporting-image count in the GENJE campaign brief; verify each asset's provenance, rights, consent and human approval. Do not publish assets with unknown rights or pending consent. |
| `donfelohke` | Prior batch: profile README and navigation links | Periodically verify public links and consistency with the canonical four-domain architecture. |
| `dwl-guile` | `README.org`, `MAINTENANCE-PLAN-2026-11-21.org` linked from README | Record exact fork and upstream commits, patches/submodules, Guile/compiler/wlroots dependency closure, build logs, Guix packaging status, runtime/session behaviour, crash recovery and rollback. The README's upstream version references are historical, not verified current source closure. |
| `home-service-dwl-guile` | `README.org`, `MAINTENANCE-PLAN-2026-11-21.org` linked from README | Verify the fork's channel URL, introduction commit and signing identity from current repository metadata before publishing installation instructions. Test service activation, Shepherd lifecycle, logs, configuration reload, failure handling and rollback. The README explicitly identifies the shown channel fingerprint as upstream, not this fork's identity. |

## Cross-repository invariants

The following architecture and governance boundaries should remain consistent:

1. Four practice domains only: NAKEBUSEN / ROOT, IKAI / MIRROR, GENJE / EXPRESSION and WARENA / CAPABILITY.
2. FELOH / F3L0H is the human authorship identity, not a fifth domain.
3. GENJE NODE is a WARENA manifestation, not a fifth domain.
4. FELOH Corpus owns shared canon and governance; specialist repositories own detailed domain records.
5. **ONLY NAKEBUSEN TRANSACTS.** IKAI remains research; GENJE remains creative practice; WARENA supplies technical capability.
6. Research, proposal, prototype, validation, release and live operation must not be conflated.
7. WARENA's libre-first, local-first, native-first and reproducibility principles must be represented accurately; a research candidate is not an approved or installed dependency.
8. Gallery assets require individual provenance, rights, consent and intended-use approval. Public availability is not permission.
9. Website publication and a successful CI build are not evidence of a successful live deployment.
10. Fork documentation must distinguish inherited upstream instructions and identities from verified fork-specific state.

## Scope limits and evidence still required

This review did not recursively inspect every file in all ten repositories, validate every internal or external link, compare every fork commit with upstream, build the software, inspect every Gallery binary, test the live website, enable GitHub Pages, or perform hardware/participant testing. Those are separate verification tasks and must not be reported as complete.

No customer data, payment credentials, private assets, account settings, repository protection settings, deployment settings or hardware were changed. No new repository was created. The review does not certify legal, tax, regulatory, safety or privacy compliance.

## Recommended closure order

1. **IKAI:** owner enables Pages; then rerun deployment and verify the portal.
2. **Website:** complete browser/mobile/accessibility and live smoke-test evidence before any production release.
3. **Gallery:** reconcile binaries, manifest, rights and consent; keep unresolved assets unpublished.
4. **Forks:** verify provenance and channel identity, then run reproducible build and service lifecycle tests.
5. **GENJE:** create the source register and creative-work record template, then document a bounded study.
6. **Corpus / WARENA / NAKEBUSEN:** continue source reconciliation and evidence closure in their respective authoritative records.

**Conclusion:** documentation coverage is broad and the domain boundaries are represented across the reviewed entry points. Full documentation quality and operational readiness remain conditional on the verification work above.
