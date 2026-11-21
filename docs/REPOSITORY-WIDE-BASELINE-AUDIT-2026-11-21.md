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


## Follow-up maintenance snapshot — 2026-11-21

This addendum preserves the original inventory and PR search snapshot above while recording subsequent maintenance activity.

### Merged documentation and maintenance PRs

- [NAKEBUSEN #24](https://github.com/donfelohke/NAKEBUSEN/pull/24) — current Corpus link and duplicate copy correction.
- [FELOH Corpus #51](https://github.com/donfelohke/feloh-corpus/pull/51) — baseline audit, README price correction and documentation index.
- [WARENA #40](https://github.com/donfelohke/WARENA/pull/40) — stale PR count and duplicate README section.
- [GENJE #29](https://github.com/donfelohke/Genje/pull/29) — four-domain architecture and governance alignment.
- [Public website #151](https://github.com/donfelohke/donfelohke.github.io/pull/151) — dated supersession notices and service-price documentation corrections.
- [Gallery #19](https://github.com/donfelohke/Gallery/pull/19) — replace missing cross-repository evidence-register links with current canon and Gallery-owned approval records.
- [IKAI #29](https://github.com/donfelohke/Ikai/pull/29) — document the disabled Pages publication setting and deployment blocker.
- [FELOH Corpus #52](https://github.com/donfelohke/feloh-corpus/pull/52) — align the Master Topic Register with the four-domain constitution.
- [Public website #147](https://github.com/donfelohke/donfelohke.github.io/pull/147) — update `actions/upload-artifact` to v7; checks passed.
- [Public website #148](https://github.com/donfelohke/donfelohke.github.io/pull/148) — update `actions/setup-node` to v7; checks passed.

[Public website #5](https://github.com/donfelohke/donfelohke.github.io/pull/5), the old `actions/configure-pages` v6 update, was closed as superseded because current `main` already pins v6.

### Remaining open PR queue

A refreshed repository-scoped search returned 16 pre-existing open PRs: 10 in `feloh-corpus` and 6 in `WARENA`; none were returned for the other eight repositories. The search index briefly continued to list merged Corpus #52; direct PR retrieval confirmed it is closed and merged. Refresh before making queue decisions.

The remaining PRs are not automatically approved. They require individual content, source, conflict and current-canon review. In particular, research branches that predate the 2026-11-20 constitution or the 2026-11-17 WARENA X11-first desktop decision must be reconciled before merging.

### Additional verified repository facts

- `donfelohke/dwl-guile` is a GitHub fork whose parent is `engstrand-config/dwl-guile`.
- `donfelohke/home-service-dwl-guile` is a GitHub fork whose parent is `engstrand-config/home-service-dwl-guile`.
- Both remain WARENA-maintained supporting forks; upstream history, licences, attribution and source provenance must be preserved. Their existence does not establish a successful WARENA build, installation or deployed Wayland session.
- IKAI's `.github/workflows/validate.yml` contains validation, Jekyll build and Pages deployment jobs. Run #105 passed validation and build but failed deployment because GitHub Pages is disabled; repository metadata reports `has_pages: false`. The settings change remains outstanding.

**Current queue count is a dated observation, not a permanent status.** The 338-file inventory above remains the initial recursive-tree snapshot; no claim is made that every file has now received a complete line-by-line review.


## Final repository reconciliation — 2026-11-21

This final same-day snapshot supersedes the earlier 16-open-PR follow-up count above. The earlier counts remain as historical observations; this section records the final state after individual review and selective integration.

### Refreshed main-branch inventory

All ten recursive Git tree requests returned truncated: false. Every repository reports main as its default branch.

| Repository | Tree entries | Documentation files |
|---|---:|---:|
| donfelohke/donfelohke.github.io | 101 | 63 |
| donfelohke/feloh-corpus | 136 | 104 |
| donfelohke/WARENA | 72 | 64 |
| donfelohke/Genje | 33 | 28 |
| donfelohke/Ikai | 79 | 56 |
| donfelohke/NAKEBUSEN | 32 | 27 |
| donfelohke/Gallery | 18 | 13 |
| donfelohke/donfelohke | 7 | 6 |
| donfelohke/dwl-guile | 34 | 3 |
| donfelohke/home-service-dwl-guile | 19 | 2 |
| **Total** | **531** | **366** |

Documentation-file counts include Markdown, reStructuredText and Org files. This is a tree inventory, not a line-by-line review of all 366 documents.

### Pull-request queue

**0 open PRs**

A fresh repository-scoped search returned zero open pull requests across all ten repositories. The initial 19-PR queue has been individually reconciled:

- Relevant research and documentation were selectively integrated into current-main PRs.
- Stale branches with superseded architecture, duplicate standards, unresolved canonical references or outdated desktop decisions were closed with an explanatory disposition.
- Website dependency updates #147 and #148 were merged after passing checks; #5 was closed because its configure-pages v6 change was already present on main.
- No branch was force-pushed or deleted.

The queue is clear; this does not mean every possible source or historical claim is verified.

### Consolidated work merged through reviewable PRs

**22 maintenance and research pull requests were merged.** The following maintenance and research integrations were merged:

- NAKEBUSEN #24; FELOH Corpus #51, #52, #53, #54, #55, #56, #57, #59, #60 and #61.
- WARENA #40, #41, #42, #43 and #44.
- GENJE #29; public website #151, #147 and #148; Gallery #19; IKAI #29.

All repository edits were made on branches and merged through pull requests. No direct commit to main, force-push or branch deletion was performed.

### Remaining blockers and uncompleted verification

1. **IKAI publication:** GitHub Pages remains disabled (has_pages: false). Workflow run #105 passed validation and Jekyll build but failed deployment with HTTP 404. Enable Pages in repository settings and verify a successful deployment before describing the Portal as live.
2. **Exact source completeness:** the complete F3L0H-PRESENT-001 edition and folder tree have not yet been verified/imported verbatim. The 2026-11-20 Master Corpus remains the accepted constitutional spine, not proof of complete transcription.
3. **Full documentation audit:** all 366 documentation files are inventoried, but not all have received line-by-line review, source verification, terminology checks or link validation.
4. **Automated checks:** a deterministic whole-repository Markdown, relative-link, index and provenance check has not yet been run across all repositories.
5. **Gallery rights:** no image is approved merely because its manifest or workflow is documented. Asset-level rights, consent, intended use and publication approval remain to be verified.
6. **Sun Burn — Black Musings:** the intake scaffold exists, but no original creative work was located or imported. Source inventory and publication intent remain incomplete / unreviewed.
7. **WARENA implementation:** Hurd, Guix, Guile, RDE and workstation documents remain research/specification. No Guix build, host installation, compositor runtime or recovery test is claimed by these documentation merges.
8. **Governance and deployment controls:** branch-protection settings, all workflow states and production deployment behaviour were not comprehensively audited.

**Final status:** repository inventory complete for the ten accessible public repositories; open PR queue cleared; selected canonical, research and provenance documentation reconciled. Full content audit, exact-source consolidation, Pages enablement, asset approval and implementation validation remain outstanding.
