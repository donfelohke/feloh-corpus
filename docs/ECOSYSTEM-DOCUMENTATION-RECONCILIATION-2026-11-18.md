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
