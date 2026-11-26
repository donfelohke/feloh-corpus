# Deep-scope ecosystem audit — 26 November 2026

**Programme:** [Coordinated revamp issue #78](https://github.com/donfelohke/feloh-corpus/issues/78)  
**Scope:** Ten existing public repositories, current default-branch READMEs, documentation indexes, workflow definitions, selected implementation/build files and recent Actions results.  
**Status:** FIRST TECHNICAL PASS · NOT A COMPLETE SOURCE, SECURITY OR ACCESSIBILITY AUDIT  
**Method:** Authenticated GitHub repository contents, workflow and run metadata, source-file inspection, and targeted searches.  
**Policy:** No new repositories; no history rewriting; preserve upstream provenance and licence obligations.

## Executive findings

1. **The fixed public price baseline is now explicit.** Retouch & Styling is KES 700; Sisterlocs Retie is KES 1,500; Artificial Locs Installation is KES 3,500. None is a starting-price estimate. Plus signs were removed from the affected current-facing website and Corpus records. The NAKEBUSEN service catalogue and website Public Facts Register remain the publication authorities.
2. **Current-facing identity drift was found and corrected.** The Corpus, public website and supporting Guile project READMEs now map GRACE → NAKEBUSEN, GRIT → WARENA and GLORY → GENJE / GENJENESS. FELOH remains the human author. Historical dated documents are not silently rewritten.
3. **IKAI had a failing deployment job despite a successful validation and Jekyll build.** The cause was a GitHub Pages deployment API 404 because Pages is not enabled. The deploy job is now fail-closed behind the repository variable `IKAI_PAGES_ENABLED=true`; validation/build continue without a false publication attempt.
4. **Most specialist repository workflows validate documentation presence, not implementation behaviour.** This is acceptable as a documentation baseline, but it is not a software test suite, build verification, reproducibility proof or runtime acceptance.
5. **The two supporting Guile repositories have no Actions workflow and no checked-in test target.** `dwl-guile` has a Makefile build path but no test target. The Guix package definition pins an older wlroots/Wayland compatibility set; a successful current build has not been established. `home-service-dwl-guile` needs a fork-specific Guix channel/provenance and activation-validation pass; its Org guide intentionally labels the shown channel example as upstream, not this fork.
6. **Website manual verification remains open.** The source and automated checks pass, but keyboard-only, TalkBack/screen-reader, physical-device, contrast, zoom/reflow and fresh live-page inspection remain separate acceptance gates.
7. **Cross-repository link integrity is not yet automatically tested.** Documentation indexes exist, but no complete automated link graph or link-check result has been established.

## Repository-by-repository baseline

| Repository | Current automated check observed | First-pass finding / next technical gate |
|---|---|---|
| `donfelohke.github.io` | Python unittest source checks; Pages build/deploy workflow | 26 site tests pass. Add/retain tests for canonical facts and language parity; perform manual mobile, keyboard, screen-reader, contrast and live deployment inspection. |
| `NAKEBUSEN` | Shell documentation-baseline workflow | Now checks all three exact fixed prices and rejects plus-sign variants. It does not test operational workflows, privacy controls or customer journey behaviour. |
| `feloh-corpus` | Shell knowledge-base baseline | Now checks required knowledge-base files, transaction boundary, exact public prices and current GLORY practice mapping. No whole-corpus link validator or schema validation yet. |
| `WARENA` | Shell documentation-baseline workflow | Validates required runbooks and headings only. No Guix build matrix, configuration evaluation, reproducibility test or real-time I/O benchmark is claimed. |
| `Ikai` | Static portal checks plus Jekyll build | Validation and build pass. Pages deployment is gated until Pages is explicitly enabled. M1 optical/display protocol remains proposed research, not an integrated prototype. |
| `Genje` | Shell documentation-baseline workflow | Validates selected governance/research files and README identity. No movement-notation parser, interoperability fixture suite or performance validation is established. |
| `Gallery` | Shell asset-governance baseline | Checks manifest and approval fields. The repository remains initialized/pending; no asset is approved merely by existing in the repository. Rights and consent remain human gates. |
| `donfelohke` | Profile README; no workflow observed | Navigation and authorship are documented. Profile bio, pinned order and account metadata remain manual account-level actions. |
| `dwl-guile` | No Actions workflow observed; Makefile build target; no Makefile test target | Build dependencies and wlroots compatibility must be pinned and tested in a reproducible Guix environment before claiming build support. Preserve upstream history/licences. |
| `home-service-dwl-guile` | No Actions workflow observed | Validate Scheme modules, Guix package evaluation, service extension/activation, channel provenance and upstream compatibility. Do not copy the upstream channel fingerprint into this fork. |

## Verified Actions evidence at this pass

- Website static validation and Pages workflow passed on the current main commit after the price and README corrections: [static validation](https://github.com/donfelohke/donfelohke.github.io/actions/runs/45783740418) · [Pages workflow](https://github.com/donfelohke/donfelohke.github.io/actions/runs/45783740280).
- NAKEBUSEN fixed-price regression workflow passed on main: [run](https://github.com/donfelohke/NAKEBUSEN/actions/runs/45784089739).
- Corpus canonical price/pillar workflow passed on main after correcting the assertion to match the README table: [run](https://github.com/donfelohke/feloh-corpus/actions/runs/45784187987).
- IKAI validation and build passed on main with deployment correctly skipped while Pages remains disabled: [run](https://github.com/donfelohke/Ikai/actions/runs/45783932244).

These results prove only the named workflow jobs and commit states. They do not prove production browser behaviour, complete dependency reproducibility, security, compliance or operational readiness.

## Merged corrections in this pass

- Website PR [#214](https://github.com/donfelohke/donfelohke.github.io/pull/214): fixed-price notation in active-facing historical documentation.
- Corpus PR [#89](https://github.com/donfelohke/feloh-corpus/pull/89): fixed-price canon in the Corpus README.
- Website PR [#215](https://github.com/donfelohke/donfelohke.github.io/pull/215): current public README identity and fixed prices.
- dwl-guile PR [#10](https://github.com/donfelohke/dwl-guile/pull/10) and home-service-dwl-guile PR [#10](https://github.com/donfelohke/home-service-dwl-guile/pull/10): current identity alignment in supporting project READMEs.
- IKAI PR [#41](https://github.com/donfelohke/Ikai/pull/41): fail-closed Pages deployment gate.
- NAKEBUSEN PR [#37](https://github.com/donfelohke/NAKEBUSEN/pull/37): exact fixed-price regression checks.
- Corpus PR [#90](https://github.com/donfelohke/feloh-corpus/pull/90) and follow-up [#91](https://github.com/donfelohke/feloh-corpus/pull/91): exact fixed-price and current-pillar regression checks; final main workflow passes.

## Priority technical work queue

### P0 — Publication integrity and release evidence
- Keep the three fixed prices synchronized across the NAKEBUSEN catalogue, website Public Facts Register, website service catalogue, homepage, webcopy and Corpus summary.
- Add a repository-wide link checker with an explicit allowlist for intentional external, archived and fragment links.
- Reconcile stale dated design/copy records by adding dated supersession notes where necessary; preserve historical snapshots.
- Complete website live-page and physical-device review; record exact commit, browser/device, viewport and findings.

### P1 — Reproducible engineering and software validation
- `dwl-guile`: establish a supported Guix build definition, exact source revision and dependency closure; run clean build, static analysis and a compositor smoke test in an isolated session where feasible. Add tests only for testable behaviour and document hardware/session limitations.
- `home-service-dwl-guile`: evaluate modules against a declared Guix channel; test package/service transformations, generated Home configuration, activation and rollback. Clarify fork channel introduction only from verified repository history and keys.
- `WARENA`: turn reproducibility runbooks into machine-checkable manifests and build records; keep benchmarks separate from proposed test protocols.
- `IKAI`: validate the static site link graph and research metadata; keep capture/privacy boundaries testable before any sensing prototype.
- `GENJE`: build machine-readable movement notation fixtures and round-trip/interoperability tests only after the notation model and licence constraints are settled.

### P2 — Governance, safety and maintenance
- Verify licence compatibility and attribution at file/subtree level, especially inherited fork files and creative assets.
- Review dependency pinning, action pinning, permissions, artifact exposure and branch protection/rulesets.
- Establish backup/restore drills, maintainer continuity and periodic access review.
- Keep Gallery approval status explicit and test rejection paths as well as approval paths.

### P3 — Public experience and account presentation
- Conduct a design audit against the approved editorial/glass hybrid, preserving the text-first static architecture and no-runtime-dependency boundary.
- Review English/Kiswahili parity, keyboard and screen-reader operation, 320px reflow, zoom, safe-area behaviour and reduced motion/transparency.
- Apply the profile bio, pinned repositories, repository descriptions, topics and homepage metadata manually using the existing account settings guide.

## Audit limitations and next evidence

This pass did not clone or execute all repositories, perform a full line-by-line source audit, run local Guix builds, inspect private settings/secrets, execute screen readers or physical-device tests, verify every external URL, or independently validate legal, cultural, linguistic or regulatory claims. No security certification or WCAG conformance claim is made.

The next pass should use isolated checkouts and reproducible environments, record exact toolchain/source versions, run targeted tests, inspect diffs and publish one evidence-backed finding register per specialist repository. Unknowns stay marked UNKNOWN until evidence exists.

**ONE CORPUS → MANY VIEWS → ONE PRACTICE.**
