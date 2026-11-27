# Account-Wide Repository Documentation Revamp — 27 November 2026

**Status:** IMPLEMENTATION IN PROGRESS / SOURCE CHANGES COMMITTED  
**Scope:** All 10 public repositories owned by @donfelohke  
**Method:** Read current repository trees and primary README/documentation indexes first; preserve repository names, history, specialist ownership and existing structure; update existing documents where possible; add research records only where a new source record was required.

## 1. Executive result

All ten repositories were inspected. Eight received documentation, navigation, public-facts or validation updates. Two specialist repositories — IKAI and GENJE — were reviewed and retained their existing 27 November README and documentation-index alignment because their current records already reflected the latest approved architecture and research state.

The public website HTML was updated to show the current approved starting-price notation:
- Retouch & Styling — **from KES 700+**.
- Sisterlocs Retie — **from KES 1,500+**.
- Artificial Locs Installation — **KES 3,500 fixed**.

The page remains a one-page static, bilingual, text-first publication. No framework, JavaScript runtime, analytics, remote font dependency, new image asset or payment integration was introduced.

## 2. Repository coverage

| Repository | Audit result | Change result |
|---|---|---|
| donfelohke | Profile README and featured-repository hierarchy inspected | README refreshed with current canonical architecture and new research links |
| donfelohke.github.io | Website README, page source, docs index, facts, copy, specs, tests and workflow inspected | Page price labels, documentation, changelog and regression tests updated |
| NAKEBUSEN | Business README, service catalogue, docs index and canonical addendum inspected | Starting-price semantics, canonical link routing and validation workflow updated |
| WARENA | README, docs index, knowledge-base index and architecture scope inspected | Two new research briefs; README and indexes updated |
| feloh-corpus | Shared constitution, docs index, audit and account guide inspected | New canonical synthesis; README, docs index and master audit updated |
| Ikai | README, docs index and canonical alignment inspected | No changes required; current research and privacy boundaries retained |
| Genje | README, docs index and canonical alignment inspected | No changes required; current livecoding and provenance links retained |
| Gallery | README, docs index and approval model inspected | Docs index updated with canonical alignment |
| dwl-guile | README, docs index and upstream boundary inspected | Broken canonical-alignment link corrected; supporting-project scope retained |
| home-service-dwl-guile | README, docs index and upstream/channel provenance inspected | Broken canonical-alignment link corrected; upstream channel safeguards retained |

## 3. Exact files changed

### donfelohke
- README.md

### donfelohke.github.io
- README.md
- index.html
- CHANGELOG.md
- tests/test_site.py
- docs/README.md
- docs/SERVICE-CATALOG.md
- docs/WEBCOPY.md
- docs/PUBLIC-FACTS-REGISTER.md
- docs/FELOH-CANONICAL-ALIGNMENT-2026-11-27.md
- docs/WEBSITE-ACCEPTANCE-CHECKLIST.md
- docs/SITE-ARCHITECTURE.md
- docs/INFORMATION-DEPTH.md
- docs/WEB-DESIGN-STANDARDS.md
- docs/UI-UX-PRODUCT-SPEC.md
- docs/NATIVE-EXPERIENCE-SYSTEM.md
- docs/BRAND-MANUAL.md
- NAKEBUSEN-MASTER-IMPLEMENTATION-BRIEF.md
- docs/AUDIENCE-MARKET-RESEARCH.md
- docs/BEAUTY-TECH-RESEARCH.md
- docs/BRAND-IMPLEMENTATION-CHECKLIST.md
- docs/NAVIGATION-BRAND-UX-RESEARCH.md
- docs/WEBSITE-AUDIT-DISCREPANCY-REGISTER.md
- docs/NAKEBUSEN-NG-GLASS-PROTOTYPE-SPEC-2026-11-24.md
- docs/FELOH-HOMEPAGE-IMPLEMENTATION-SPEC-2026-11-27.md
- docs/ECOSYSTEM.md
- docs/WEBSITE-COPY-RESEARCH-AND-IMPLEMENTATION-2026-11-19.md
- docs/UI-UX-RESEARCH-2026-11-19.md
- docs/BRAND-RESEARCH-VALIDATION.md
- docs/brand-business-blueprint.md
- docs/REPOSITORY-UPGRADE-PLAN-2026-11-21.md
- research/nakebusen-market-customer-research-2026-10.md
- docs/PR-RECONCILIATION-2026-10-25.md

### NAKEBUSEN
- README.md
- docs/README.md
- docs/service-catalogue.md
- docs/FELOH-CANONICAL-ALIGNMENT-2026-11-27.md
- .github/workflows/validate.yml

### WARENA
- README.md
- docs/README.md
- docs/knowledge-base-index.md
- docs/research/WARENA-FREEDOM-IN-MACHINE-LEARNING-RESEARCH-2026-11-27.md (new)
- docs/research/WARENA-UTILITY-SHELL-KERNEL-AND-COMPOSABLE-SYSTEMS-RESEARCH-2026-11-27.md (new)

### feloh-corpus
- README.md
- docs/README.md
- docs/FELOH-GITHUB-ECOSYSTEM-MASTER-AUDIT-2026-11-27.md
- docs/FELOH-CANONICAL-RESEARCH-SYNTHESIS-2026-11-27.md (new)

### Gallery
- docs/README.md

### dwl-guile
- README.md

### home-service-dwl-guile
- README.md

The account settings guide was also updated in the preceding account-profile tranche:
feloh-corpus/docs/GITHUB-ACCOUNT-REVAMP-MANUAL-SETTINGS-2026-11-24.md.

## 4. New canonical and research records

### FELOH Corpus
FELOH Canonical Research Synthesis now consolidates:
- Human authorship and GRACE / GRIT / GLORY.
- NAKEBUSEN, WARENA, IKAI, GENJE, FELOH Corpus and Gallery responsibilities.
- Canonical brand interpretations and linguistic evidence qualifications.
- Commercial boundary and current service-price semantics.
- Research versus implementation vocabulary.
- Repository ownership and governance rules.

### WARENA
Freedom in Machine-Learning Applications evaluates freedom across application code, model architecture, weights, training, data, runtime, hardware, deployment and governance. The FSF announcement is a research lead, not a completed audit or platform selection.

Utility Shell, Kernel Boundaries and Composable Systems separates shell, kernel, IPC, service supervision, utility services and real-time I/O. It explicitly does not claim an implemented kernel, operating system or product.

## 5. Validation and workflow status

- Updated WARENA README, documentation index and knowledge-base index were committed; repository validation workflows were observed passing for the new research/index commits.
- NAKEBUSEN's updated documentation-baseline workflow passed after its validation rules were updated to accept KES 700+ and KES 1,500+ as starting prices while retaining KES 3,500 as fixed.
- The website static-site validation passed at commit 971eea31d5a885d1c7ffb2bd953a0160039b8997. The subsequent Pages deployment run for commit a17af99b3ec42b1827c97c248f64b01d31c14465 was pending at the last check; confirm its completion before claiming the newest docs revision was deployed. The page/test source revision at 665c37e8b45b9b0f7e1a81c53ca37d46019d010f had both validation and Pages deployment pass.
- The site regression tests were updated to assert the two starting prices and one fixed price. Browser-level visual inspection, responsive review, accessibility review and a fresh public-page fetch remain separate release checks.

## 6. Deliberately unchanged

- Repository names, branch names, commit history and existing source ownership.
- IKAI and GENJE specialist documentation already aligned to the current 27 November direction.
- Gallery assets and publication approvals.
- Payment details and payment flow; no API, STK push, automated verification or simulated success state was introduced.
- No repository creation, deletion, archive, rename, fork or wholesale rewrite.
- No new application runtime or framework.

Historical documents remain historical. Their dated claims should not be rewritten as if they had been true at the time; current guidance is governed by the latest canonical and specialist source records.

## 7. Remaining work

1. Confirm the website validation and Pages workflow outcomes; resolve any failing regression assertions before treating the page as release-ready.
2. Perform a browser-level visual and accessibility review of the deployed page, including English/Kiswahili parity and mobile navigation.
3. Finish GitHub account-level metadata and pin ordering through account settings; these are separate from repository file commits.
4. Continue the detailed specialist audits and technical validations without converting research briefs into implementation claims.

**Governance rule:** exact changed files, commit references, test outcomes and unresolved limitations must accompany each further tranche.

**ONE CORPUS → MANY VIEWS → ONE PRACTICE.**


## 8. Supplemental current-spec and supersession updates

The subsequent full-text search found additional current-facing specifications and dated supersession notices that still carried the prior fixed-price interpretation. These were reconciled without rewriting the historical body of older research records.

Additional website files changed:
- docs/FELOH-HOMEPAGE-IMPLEMENTATION-SPEC-2026-11-27.md
- docs/ECOSYSTEM.md
- docs/WEBSITE-COPY-RESEARCH-AND-IMPLEMENTATION-2026-11-19.md
- docs/UI-UX-RESEARCH-2026-11-19.md
- docs/BRAND-RESEARCH-VALIDATION.md
- docs/brand-business-blueprint.md
- docs/REPOSITORY-UPGRADE-PLAN-2026-11-21.md
- research/nakebusen-market-customer-research-2026-10.md
- docs/PR-RECONCILIATION-2026-10-25.md

The website Public Facts Register, acceptance checklist, current canonical alignment, public service catalogue, native experience specification, design standards and discrepancy register now consistently distinguish the two starting prices from the fixed Artificial Locs Installation price.

## 9. Additional validation evidence

- NAKEBUSEN documentation-baseline workflow: **PASS** at commit 0bd3f39c7bb2813091986d55b4961d4479af683c.
- Website static-site validation: **PASS** at commit e8cd336909e21daf4598311b071741d48eb302aa.
- Website Pages deployment: a successful deployment was observed at commit 665c37e8b45b9b0f7e1a81c53ca37d46019d010f, which contains the updated HTML price labels. A later documentation-only commit triggered another Pages workflow; its status should be checked independently.
- The public-page text fetch returned older price labels despite the successful source/deployment run. Treat that fetch as stale or not yet refreshed; do not claim a fresh independent live-render verification until the public response reflects the updated source.


## 10. Page-level price disclosure

The website's English and Kiswahili LOCS footnote now explicitly states that Retouch & Styling and Sisterlocs Retie are starting prices, while Artificial Locs Installation is fixed at KES 3,500. The wording is also recorded in docs/WEBCOPY.md and the website changelog. Regression tests assert both language disclosures.

The site static test suite passed at commit fc0cb0302cff4a3e2457e34df9f3c3774ca5d943. A later docs-only update triggered another run; the latest Pages deployment remained queued at the time of this note.
