# COMPUTE + ARTS — Claim and Evidence Register

**Version:** 0.1 · **Record date:** 2026-10-25  
**Purpose:** Bounded claim ledger for this programme; supplements rather than replaces the general claim ledger.

## Status vocabulary

- **SUPPORTED — SOURCE REVIEWED:** cited source supports the narrow wording.
- **REPORTED — NOT INDEPENDENTLY TESTED:** a source reports a finding or project status.
- **INTERPRETATION:** reasoned implication, not a direct source claim.
- **HYPOTHESIS:** requires empirical testing.
- **RECOMMENDATION:** proposed action, not established fact.
- **UNKNOWN / NOT VERIFIED:** evidence is insufficient.
- **LEGAL REVIEW REQUIRED:** legal text identified but currentness/applicability not determined.

## Claims

| ID | Statement | Label | Sources | Review state and limitations |
|---|---|---|---|---|
| CA-CL-001 | TidalCycles documents a pattern-based system for livecoding music and composition, with SuperDirt as its default sound engine. | SUPPORTED — SOURCE REVIEWED | CA-004, CA-005 | Official overview reviewed. Pin versions and test Linux setup before claiming compatibility. |
| CA-CL-002 | TidalCycles is suitable for an E-Genge livecoding prototype. | HYPOTHESIS | CA-004–CA-006 | Not tested. Compare expressive control, workflow fit, timing, setup burden and sample rights with a performer. |
| CA-CL-003 | Wits AI & African Music supports artist–engineer collaborations around African music, archiving, performance and tool development. | SUPPORTED — SOURCE REVIEWED | CA-001, CA-002 | Official programme description reviewed. Scope is not proof that any prototype works or is community-approved. |
| CA-CL-004 | Wits reported five artist–engineer teams showcased prototypes on 16 April 2026. | REPORTED — NOT INDEPENDENTLY TESTED | CA-002 | Institutional report reviewed. Inspect demos, project pages, publications and licences before capability claims. |
| CA-CL-005 | Laban/Bartenieff-related movement analysis describes qualitative aspects and relationships of movement. | SUPPORTED — SOURCE REVIEWED | CA-007 | Institutional overview reviewed. Primary scholarship and practitioner perspectives remain to be reviewed. |
| CA-CL-006 | A movement-to-sound interface can support expression without ranking or diagnosing participants. | HYPOTHESIS | CA-007; IKAI README | Not tested. Requires participant-directed trials, privacy and accessibility review; concept alone proves nothing. |
| CA-CL-007 | FAIR principles concern findability, accessibility, interoperability and reusability of research objects, including data, algorithms and workflows. | SUPPORTED — SOURCE REVIEWED | CA-009 | Article abstract/page reviewed. Full-paper review required for formal synthesis; FAIR does not grant permission. |
| CA-CL-008 | Software Heritage provides infrastructure for preserving source code and development history. | SUPPORTED — SOURCE REVIEWED | CA-010, CA-011 | Official pages reviewed. Check a specific origin before claiming it is archived; archive status does not grant reuse rights. |
| CA-CL-009 | GNU Guix documents build isolation mechanisms intended to support reproducible builds. | SUPPORTED — SOURCE REVIEWED | CA-012 | Manual excerpt reviewed. Specific builds need testing and independent reproduction. |
| CA-CL-010 | Kenya's Protection of Traditional Knowledge and Cultural Expressions Act addresses prior informed consent and acknowledgement in relevant uses. | LEGAL REVIEW REQUIRED | CA-013 | Legal text/excerpts reviewed. Verify current official text, exceptions and facts; seek Kenyan legal advice before relying on an interpretation. |
| CA-CL-011 | The linked Copyright Act revision page describes coverage including literary, musical, artistic, audiovisual works and sound recordings. | SUPPORTED — SOURCE REVIEWED | CA-014 | Agency page/revision note reviewed. Revision marked 2009; current amendments and AI questions require further legal research. |
| CA-CL-012 | A creative archive should preserve originals and record derivatives, provenance, permissions, access conditions and rights. | RECOMMENDATION | CA-009, CA-013, CA-016 | Design recommendation. Validate with archivists, rights holders and relevant communities. |
| CA-CL-013 | Code reproducibility does not guarantee identical artistic output across different hardware, audio stacks or runtime conditions. | INTERPRETATION | CA-004–CA-006, CA-012 | Technical inference. Define reproducibility levels and test named environments; document nondeterminism and equipment dependence. |
| CA-CL-014 | GENJE, WARENA and IKAI READMEs describe research/documentation baselines and do not claim proposed systems are fully operational. | SUPPORTED — REPOSITORY README REVIEWED | Repository READMEs | README content inspected 2026-10-25. Audit code, tests, releases and runtime behaviour before stronger maturity claims. |
| CA-CL-015 | The FELOH Corpus has research bibliography, source-inventory folders and a claim-ledger scaffold. | SUPPORTED — REPOSITORY TREE INSPECTED | FELOH Corpus research directory | Main-branch listings inspected 2026-10-25. Not a complete content audit. |
| CA-CL-016 | A local-first creative workspace can meet project needs without mandatory cloud processing. | HYPOTHESIS | WARENA README; IKAI README | Not tested. Threat-model network calls and verify offline operation. |
| CA-CL-017 | Current source set is sufficient for a systematic review of COMPUTE + ARTS. | UNKNOWN / NOT VERIFIED | CA-001–CA-016 | Not established. Define databases, search strings, time range, criteria, screening and duplicate handling; expand primary literature. |

## Repository evidence recorded

### Inspected
- FELOH Corpus: README, research README, master bibliography, general claim ledger, and listings for bibliography, claims and source inventory.
- GENJE: README and root listing.
- WARENA: README and root listing.
- IKAI: README and root listing.
- Public profile repository: README.
- Open Corpus PR metadata: #5, #7, #8, #9, #10, #11 and #12. Existence and titles checked; this is not full diff/check review.

### Not yet inspected or tested
- Complete recursive file trees and all documents in specialist repositories.
- CI runs, branch rules, Pages deployment, package/build checks and runtime behaviour across all repositories.
- Full diffs, dependencies and review threads for all open PRs.
- Full text of every cited scholarly source and primary movement-studies sources.
- Current consolidated Kenyan legal texts and legal advice.
- Interviews, community consultation, ethics review or consent for cultural material.
- Prototype code, audio output, sensor paths, offline behaviour or reproducibility.

## Search and review log

| Date | Action | Result | Limitation |
|---|---|---|---|
| 2026-10-25 | Web search for African music and AI | Located Wits AIAM and 2026 showcase report | Institutional source; project-level evidence needed |
| 2026-10-25 | Reviewed TidalCycles docs | Documented architecture and Linux setup guide found | No install/build test |
| 2026-10-25 | Searched movement analysis | Laban/Bartenieff institutional overview found | Primary scholarship not fully inventoried |
| 2026-10-25 | Searched FAIR and software preservation | FAIR article and Software Heritage docs found | No archive or metadata audit |
| 2026-10-25 | Searched Kenyan cultural rights/copyright | WIPO Lex text and Copyright Act revision page found | Current law/application not determined |
| 2026-10-25 | Inspected connected GitHub repositories | Existing research scaffold and domain READMEs found | Repository-wide audit incomplete |
| 2026-10-25 | Inspected open Corpus PR metadata | Found source-first research PR #9 and related documentation PRs | Full diff/check/dependency reconciliation pending |

## Maintenance rules

1. Assign stable IDs; do not silently change a claim's meaning.
2. Keep exact source URLs, dates and supporting sections/pages.
3. Seek counterevidence for consequential claims.
4. Say when a source is unavailable; do not infer its contents.
5. Separate reported claims from independently reproduced results.
6. Identify jurisdiction and legal version; seek specialist review where needed.
7. For cultural material, record authority, consent, access restrictions and permitted uses. Public availability is not permission.
8. Update implementation maturity only after inspecting code and recording test evidence.
9. Record the PR or commit that changed this register.
