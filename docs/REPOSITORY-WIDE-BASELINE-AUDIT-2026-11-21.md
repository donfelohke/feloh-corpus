# Repository-wide baseline audit — 2026-11-21

**Owner:** FELOH Corpus  
**Scope:** All ten repositories accessible under `@donfelohke` through the connected GitHub account.  
**Purpose:** Establish a reproducible inventory baseline for documentation maintenance.  
**Status:** INVENTORY SNAPSHOT · PARTIAL CONTENT AUDIT · NOT A RELEASE CERTIFICATION

## Executive result

- **10 repositories** inspected; each reports `main` as its default branch.
- **495 Git tree entries** enumerated across the ten repositories.
- **338 Markdown / reStructuredText / Org documentation files** counted from the recursive Git trees.
- **19 open pull requests** observed in the current PR search snapshot: 10 in `feloh-corpus`, 6 in `WARENA`, and 3 in `donfelohke.github.io`.
- All ten recursive tree responses reported `truncated: false`.

The file count is an inventory of documentation-like files, not proof that every file has received a line-by-line editorial, technical, link, security or factual review.

## Repository inventory

| Repository | Tree entries | Documentation files | Primary responsibility |
|---|---:|---:|---|
| `donfelohke/donfelohke.github.io` | 101 | 63 | Public NAKEBUSEN website, copy, accessibility and deployment evidence |
| `donfelohke/feloh-corpus` | 110 | 84 | Shared canon, governance, evidence, provenance and indexes |
| `donfelohke/WARENA` | 62 | 56 | Systems architecture, technology policy, configuration and runbooks |
| `donfelohke/Genje` | 33 | 28 | Creative practice, Genge, movement, music and livecoding |
| `donfelohke/Ikai` | 79 | 56 | Reflective-computing research, Portal and validation |
| `donfelohke/NAKEBUSEN` | 32 | 27 | ROOT practice, service catalogue and commercial operations |
| `donfelohke/Gallery` | 18 | 13 | Asset provenance, rights, consent and approval |
| `donfelohke/donfelohke` | 7 | 6 | Public author profile and portfolio navigation |
| `donfelohke/dwl-guile` | 34 | 3 | Supporting Guile-native compositor fork |
| `donfelohke/home-service-dwl-guile` | 19 | 2 | Supporting Guix Home service fork |
| **Total** | **495** | **338** | |

The two supporting fork repositories use `README.org`, not `README.md`; the initial Markdown README fetch therefore returned not found, while recursive tree inspection confirmed their actual documentation files.

## Open pull-request snapshot

The following open PRs were returned by repository-scoped searches on 2026-11-21. This is a queue inventory, not an endorsement to merge.

### FELOH Corpus — 10

- [#33](https://github.com/donfelohke/feloh-corpus/pull/33) — Before Africa sources, materials and population evidence
- [#32](https://github.com/donfelohke/feloh-corpus/pull/32) — Reflective computing and Labanotation source brief
- [#31](https://github.com/donfelohke/feloh-corpus/pull/31) — UNESCO General History of Africa source framework
- [#19](https://github.com/donfelohke/feloh-corpus/pull/19) — Cross-domain sources, claims and learning paths
- [#17](https://github.com/donfelohke/feloh-corpus/pull/17) — Annotated master resource register
- [#15](https://github.com/donfelohke/feloh-corpus/pull/15) — Heritage, knowledge sovereignty, NAKEBUSEN beauty and technology
- [#13](https://github.com/donfelohke/feloh-corpus/pull/13) — COMPUTE + ARTS programme and bibliography
- [#11](https://github.com/donfelohke/feloh-corpus/pull/11) — Institutional documentation framework
- [#9](https://github.com/donfelohke/feloh-corpus/pull/9) — Source-first version-controlled research system
- [#5](https://github.com/donfelohke/feloh-corpus/pull/5) — Sun Burn / Black Musings archive scaffold

### WARENA — 6

- [#33](https://github.com/donfelohke/WARENA/pull/33) — GNU Hurd and Guix integration progress
- [#21](https://github.com/donfelohke/WARENA/pull/21) — Foundational computer science and research references
- [#19](https://github.com/donfelohke/WARENA/pull/19) — EliteBook sovereign Emacs and agent workstation setup
- [#15](https://github.com/donfelohke/WARENA/pull/15) — WSAS and upstream provenance alignment
- [#14](https://github.com/donfelohke/WARENA/pull/14) — GNU Guile ecosystem audit
- [#12](https://github.com/donfelohke/WARENA/pull/12) — RDE + DWL-Guile reuse audit

### Public website — 3

- [#147](https://github.com/donfelohke/donfelohke.github.io/pull/147) — `actions/upload-artifact` dependency update
- [#148](https://github.com/donfelohke/donfelohke.github.io/pull/148) — `actions/setup-node` dependency update
- [#5](https://github.com/donfelohke/donfelohke.github.io/pull/5) — `actions/configure-pages` dependency update

No open PRs were returned by these searches for Genje, Ikai, NAKEBUSEN, Gallery, the profile repository, dwl-guile or home-service-dwl-guile. Search results are a dated snapshot and should be refreshed before queue decisions.

## Confirmed maintenance corrections

1. **NAKEBUSEN README:** PR [#24](https://github.com/donfelohke/NAKEBUSEN/pull/24) was merged on 2026-11-21. It replaces the obsolete 2026-10-26 architecture pointer with the accepted 2026-11-20 Master Corpus and removes duplicated service-availability wording. No prices, payment details, service scope or business terms were changed.
2. **Corpus public price summary:** this README's Artificial Locs Installation price is corrected to **KES 3,500**, without a plus sign, matching the NAKEBUSEN service catalogue and Public Facts Register.
3. **Corpus editorial duplication:** the repeated statement that NAKEBUSEN is the sole commercial interface is consolidated without changing the rule.
4. **PR queue counts:** the upgrade plan's earlier figure of 28 open PRs is superseded by this dated observation of 19. The WARENA plan's earlier figure of eight is likewise superseded by the six returned in the same snapshot.

## Canonical architecture and operating constraints

The audit preserves the accepted four-domain model:

- **NAKEBUSEN / ROOT** — only live commercial practice and transaction interface.
- **IKAI / MIRROR** — reflective-computing research; not a released product.
- **GENJE / EXPRESSION** — embodied creative and cultural practice; not a checkout brand.
- **WARENA / CAPABILITY** — systems engineering and infrastructure.

F3L0H is the overarching human authorship identity, not a fifth domain. Gallery, website, profile and supporting forks are repository roles, not additional practice domains. GENJE NODE is a WARENA manifestation, not a fifth domain.

Technology constraints remain: WARENA/IKAI are native-first, libre-first and local-first; JavaScript and web technologies are excluded as their application/runtime architecture. The desktop research direction remains X11-first. Research, design, prototype, validation, release and deployment must remain distinct maturity states.

## Audit limitations and next work

This baseline did not establish:

- whether branch protection or required reviews are enabled;
- whether every workflow, build, test or deployment currently passes;
- whether every cross-repository link resolves;
- whether all open PRs are non-conflicting, current or safe to merge;
- whether all claims in every document have adequate source evidence;
- whether a documented capability is installed, deployed or field-tested;
- whether assets in Gallery have rights, consent or publication approval;
- whether the complete F3L0H-PRESENT-001 source edition has been imported.

Next work is to review open PRs individually against current canonical documents; inspect exact source provenance and missing corpus material; run deterministic Markdown/link/index checks; review the website's existing test workflow; reconcile the WARENA, IKAI and GENJE research queues; and verify fork lineage and build/test state. Do not bulk-merge PRs or infer implementation from documentation.

**Audit rule:** inventory is not validation; a commit is not deployment; a merge is not approval of every claim inside a repository.
