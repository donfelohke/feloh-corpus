# Ecosystem Documentation Reconciliation — 2026-11-18

**Owner:** FELOH Corpus  
**Scope:** Ten maintained public repositories, default branch `main`  
**Method:** Repository tree inventory, primary README/index inspection, selected policy and service-document comparison, open-PR inventory.  
**Status:** Rolling audit; not a certification that every line in every file has been reviewed.

## Authority and change rules

- `feloh-corpus` owns shared terminology, cross-project relationships, governance, evidence labels and source routing.
- Specialist repositories own their domain implementation and operating documentation.
- The public website owns rendered behaviour, page copy and release evidence.
- NAKEBUSEN owns its service catalogue, public offer and commercial terms. **ONLY NAKEBUSEN TRANSACTS.**
- WARENA owns systems architecture, stack policy, Guix/RDE configuration and technical runbooks.
- IKAI owns reflective-computing research and privacy constraints.
- GENJE owns creative practice, movement, notation, livecoding and provenance.
- Gallery owns asset intake, provenance, rights and approval state.
- The two WARENA forks retain upstream history; fork-specific maintenance and deployment maturity must be stated separately.
- A document, branch, merge or passing source-level test does not prove a deployed capability.

## Repository inventory

| Repository | Documentation responsibility | Main-branch review |
|---|---|---|
| `feloh-corpus` | Shared canon, governance, research registers, documentation map | README, documentation tree, docs index, technology policy and selected research notes |
| `WARENA` | Systems architecture, stack register, desktop, Guix/RDE and runbooks | README, knowledge-base index, desktop architecture, desktop decision, technology constitution, stack register |
| `NAKEBUSEN` | Service catalogue, operating procedures, privacy, customer journeys | README, knowledge-base index, service catalogue |
| `Genje` | Creative identity, livecoding, movement notation, performance and provenance | README, foundations and knowledge-base index |
| `Ikai` | Reflective-compute research, spatial computing, privacy and research protocol | README, knowledge-base index and research alignment |
| `donfelohke.github.io` | Website copy, design, accessibility, browser tests, deployment and recovery | README, documentation tree pointer, brand canon and acceptance checklist |
| `Gallery` | Asset manifest, rights, curation and approvals | README, asset manifest and approval workflow |
| `donfelohke/donfelohke` | Public profile and portfolio navigation | README and portfolio identity record |
| `dwl-guile` | WARENA-maintained Guile/Wayland compositor fork | README and man-page documentation |
| `home-service-dwl-guile` | WARENA-maintained Guix Home service fork | README and service examples |

## Confirmed corrections and precedence

1. **Service naming:** the approved public loc service label is **Sisterlocs Retie**. The corpus and profile copies using “LOCS Retie” are corrected to match the NAKEBUSEN service catalogue and website.
2. **Desktop policy:** the 2026-11-17 WARENA Technology Constitution and latest X11-first decision supersede older summaries that present Niri + Noctalia as the leading WARENA desktop direction. Keep Wayland/dwl-guile as secondary/experimental; keep Sway as comparison/recovery baseline.
3. **GNUstep bridge:** the historical GNUstep-Guile bridge is not a supported Guile 3 / GOOPS integration. The compatibility audit is indexed in WARENA; do not imply a successful modern build.
4. **IKAI:** research status remains WIP. No mirror prototype, sensor pipeline, user study, XR deployment or clinical/biometric capability is claimed.
5. **GENJE:** movement notation and livecoding references are research and practice documentation. They do not imply motion-capture implementation, automated interpretation or a validated movement dataset.
6. **Gallery:** candidate assets remain proposed until source bytes, provenance, rights, intended use and consent are checked. A brief or manifest entry does not approve an asset.
7. **Website:** acceptance checklists are test plans until actual browser, mobile, accessibility and production checks are recorded.
8. **Forks:** WARENA fork ownership does not mean upstream project ownership, a successful Guix package, or a deployed desktop session.

## Remaining audit work

- Inspect every open documentation PR against current `main`; port only unique, still-valid material through fresh branches.
- Validate internal Markdown/Org links and stale dates across the complete corpus.
- Reconcile duplicated portfolio summaries and old candidate-stack language in remaining historical documents.
- Verify website public copy against NAKEBUSEN's current catalogue and payment-release decisions.
- Preserve research provenance, licences, attribution and consent in Gallery and GENJE.
- Record test outputs before marking any implementation or deployment gate complete.

## Review limitations

This pass inventories the documentation tree and inspects primary entry points and selected high-impact policy files. It is not a line-by-line review of every historical research source, a link checker run, a legal review, an accessibility certification, or a build/deployment verification. Unreviewed material remains unverified rather than presumed correct.


## Documentation corrections merged — 2026-11-18

The following main-based documentation changes were merged after review of their patches. These are source-document corrections, not software deployment claims.

| Repository | Merged PR | Scope |
|---|---|---|
| FELOH Corpus | [#41](https://github.com/donfelohke/feloh-corpus/pull/41), [#42](https://github.com/donfelohke/feloh-corpus/pull/42) | Service-label canon, documentation audit, XLibre compatibility wording |
| WARENA | [#27](https://github.com/donfelohke/WARENA/pull/27), [#28](https://github.com/donfelohke/WARENA/pull/28), [#29](https://github.com/donfelohke/WARENA/pull/29) | GNUstep/GOOPS compatibility, X11-first desktop policy, stack/index precedence |
| GENJE | [#20](https://github.com/donfelohke/Genje/pull/20), [#21](https://github.com/donfelohke/Genje/pull/21) | Movement-score and livecoding research, primary-documentation links |
| IKAI | [#19](https://github.com/donfelohke/Ikai/pull/19), [#20](https://github.com/donfelohke/Ikai/pull/20), [#21](https://github.com/donfelohke/Ikai/pull/21) | Reflective-computing research and current workstation-policy alignment |
| NAKEBUSEN | [#17](https://github.com/donfelohke/NAKEBUSEN/pull/17) | Service validation wording and WARENA desktop-policy reference |
| Gallery | [#15](https://github.com/donfelohke/Gallery/pull/15) | Desktop-policy reference alignment; asset approval rules preserved |
| Profile | [#11](https://github.com/donfelohke/donfelohke/pull/11) | Service-label correction and portfolio source-of-truth wording |
| Website | [#126](https://github.com/donfelohke/donfelohke.github.io/pull/126) | Approved homepage proposition, documentation ownership and release evidence |
| `dwl-guile` fork | [#1](https://github.com/donfelohke/dwl-guile/pull/1) | Historical upstream baseline and fork maturity |
| `home-service-dwl-guile` fork | [#1](https://github.com/donfelohke/home-service-dwl-guile/pull/1) | Upstream channel versus maintained-fork boundary |

## Remaining PR backlog

The open PR backlog remains a separate reconciliation queue. No mass merge or mass close was performed. Older website PR #109 remains held for service-label and payment-footer conflicts. PRs with useful but stale branches must be compared with current `main` and ported selectively.
