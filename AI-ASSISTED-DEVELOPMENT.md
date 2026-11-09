# AI-Assisted Development, Source Integrity and Provenance

**Status:** Governance policy — proposed for review  
**Applies to:** Original code, documentation, research, specifications, datasets, creative work and generated artefacts across the FELOH repository ecosystem.

## 1. Purpose

Protect human authorship, lawful reuse, source attribution, research integrity and reproducibility when using generative AI or other automated development tools. An LLM rewrite does not erase the provenance or rights obligations of its inputs.

This policy responds to documented risks of unauthorised source extraction, unattributed copying and AI-assisted attempts to disguise copied implementation. It does not assert that any particular person or project committed misconduct beyond what cited, reviewed evidence establishes.

## 2. Core rules

- Never knowingly use leaked, stolen, access-controlled or otherwise unauthorised source material.
- Never submit copied or restricted code to an LLM to paraphrase, rename, restructure or disguise its origin.
- Never represent an LLM rewrite of third-party or unreleased implementation as independent clean-room work.
- Preserve copyright notices, licence texts, attribution, notices and source history.
- Do not treat model output, a generated citation, a similarity score or an AI explanation as proof of originality, permission, correctness or provenance.
- Human contributors remain responsible for every submitted change, including generated material.
- Do not upload secrets, credentials, private customer data, confidential correspondence or restricted source to external AI services.

## 3. Permitted assistance and disclosure

AI assistance is not categorically prohibited by this policy. It may be used where the input material is authorised for that processing and the resulting work is independently reviewed.

Disclose material AI assistance in the pull request or adjacent work record when it materially shaped code, research synthesis, specifications, translations, creative assets or substantive documentation. Record, where known: tool/provider and model/version; date and purpose; material input sources and their permission/status; files or sections materially affected; human reviewer and checks performed; unresolved uncertainty or limitations.

Routine spelling correction or low-impact editor completion need not receive a separate public record unless it affects authorship, rights or a project-specific rule.

## 4. Clean-room and reverse-engineering work

1. Record the lawful source of observations: hardware behaviour, public documentation, independently captured traces or other authorised evidence.
2. Keep observations, specifications, hypotheses and implementation code distinguishable.
3. Do not consult or prompt against leaked, unreleased or restricted implementation code.
4. Do not call work clean-room if the implementation was materially derived from unauthorised source or an LLM transformation of it.
5. Record AI assistance and independent review; where project rules require a stricter no-AI boundary, follow that rule.
6. Preserve test conditions, tool versions, traces where lawful, and reproducible steps.

## 5. Licensing policy

- GPL-first is the default preference for original software where a reciprocal licence is suitable.
- Existing repository licence grants are not changed by this policy.
- No repository is relicensed merely by adding this document.
- Do not change GPL-3.0 to GPL-2.0-or-later, or vice versa, without an explicit, documented rights-holder decision and compatibility review.
- Third-party dependencies retain their own licences and notices.
- Code, documentation, data, fonts, photographs, audio, video, artwork and other media may require different rights treatment. A root software licence must not be assumed to license every asset.
- Where ownership, contributor authority or permission is unclear, mark the item RIGHTS-UNCLEAR and do not relicense or redistribute it pending review.

## 6. Provenance and review record

For material contributions, preserve author and contributor roles; source repository, URL, version or commit; licence/permission and attribution obligations; generated or transformed inputs and material AI involvement; human review, tests, build environment and results; known limitations, disputed origin or unresolved rights; pull request and commit references.

Do not rewrite Git history to conceal origin. Corrections should be additive and traceable.

## 7. Incident response

If potentially unauthorised or unattributed material is identified, stop further distribution; preserve relevant commit, URL and review evidence without republishing restricted content; mark the contribution under provenance review; identify affected files, dependencies, releases and downstream consumers; seek rights-holder or qualified legal review where necessary; record resolution, remediation and remaining uncertainty.

## 8. Enforcement and limits

This document is a contributor policy, not an automated detector or legal opinion. It does not prove that AI use is detectable, that a derivative-work question has a simple answer, or that repository settings enforce these rules. Review, CI, signatures, access controls and attestations must be configured and verified separately.


## 9. Related documents

- [Governance](GOVERNANCE.md)
- [Contributing](CONTRIBUTING.md)
- [Evidence and Provenance Method](EVIDENCE-AND-PROVENANCE-METHOD.md)
- [GNU GPL-3.0 licence text](LICENSE)

## 10. Code laundering and derivative-source controls

### 10.1 Definition

For this policy, **code laundering** means concealing or misrepresenting the origin, authorship, licence, access status or derivation of source code or other protected material. Examples include submitting leaked, confidential, unreleased or otherwise unauthorised material to an LLM and asking it to paraphrase, translate, rename, refactor, summarise into implementation instructions or regenerate that material; manually performing the same transformation; removing notices or history; or presenting a materially derived result as independent work. The same principle applies to documentation, datasets and creative assets.

A change in syntax, language, names, formatting, architecture or textual similarity does not by itself establish independent authorship, lawful use or clean-room provenance. This policy does not presume that every similarity is misconduct; assess evidence and rights carefully.

### 10.2 Prohibited conduct

Contributors MUST NOT:

- knowingly obtain, retain, upload, prompt against, transform, reproduce or distribute leaked, stolen, access-controlled, confidential, unreleased or otherwise unauthorised source material;
- use an AI system, code translator, formatter, refactoring tool, human intermediary or other transformation process to conceal copying, evade attribution, remove licence obligations or manufacture a false clean-room record;
- remove or falsify copyright headers, licence notices, authorship, commit history, source references or provenance records;
- claim independent implementation, clean-room development, original authorship or licence compatibility when the evidence does not support that claim;
- treat AI output, a negative similarity scan, a model's assurance, or the absence of a known match as proof that the output is original or legally reusable.

### 10.3 Source-input and contribution record

For material code contributions, the PR must identify the relevant source classes and material references: project-owned code; upstream repositories and exact commits/tags; documentation/specifications; dependencies and generated files; public observations or independently collected test results; and AI/tool assistance that materially shaped the contribution. Record URLs, versions or commit hashes, retrieval dates where practical, applicable licences/permissions, required notices, affected paths, and the human reviewer. Record unknowns explicitly; do not invent provenance.

A contributor need not publish confidential prompts or sensitive source contents. Record enough metadata to support review without copying restricted material into the repository. If source material cannot lawfully be disclosed or its status cannot be established, stop using it and escalate for review.

### 10.4 AI tool and output review

Before using an AI tool for a material contribution, check its terms, data retention/training settings where available, confidentiality suitability and whether the intended inputs are authorised for that service. Do not submit third-party code merely because it is publicly accessible; check its licence and project rules. Review generated output for recognisable third-party material, licence notices, suspiciously specific implementation details, security defects and unsupported claims. Similarity scanners and model safeguards are useful signals only, not legal clearance.

If output appears to reproduce or closely track third-party material, do not merge it pending source identification, permission/licence review and attribution. Preserve the evidence and disclose the uncertainty.

### 10.5 Clean-room claims

A clean-room claim requires a documented independent process, not merely a rewritten codebase. At minimum:

1. Define the permitted evidence set before implementation: public specifications, lawful documentation, independently observed behaviour, hardware measurements, protocol traces lawfully obtained, and other authorised material.
2. Exclude restricted implementation source and any AI output materially derived from it from the implementation inputs.
3. Where risk warrants, separate source researchers from implementers; give implementers only the independently written specification and permitted evidence.
4. Record the specification's authorship, sources, date, revisions, access boundaries and implementation review.
5. Preserve tests and observations that demonstrate behaviour without copying protected implementation expression.
6. State limitations. If restricted material contaminated the implementation path, do not describe the result as clean-room; quarantine it and seek a fresh, genuinely independent process or rights-holder permission.

A clean-room process is not a guarantee against all legal claims. Obtain qualified legal advice for material disputes or high-risk releases.

### 10.6 Suspected laundering or provenance failure

Any contributor or maintainer may raise a good-faith provenance concern privately or in the PR. Do not publicly accuse a person or project without substantiated evidence. On a credible concern, maintainers should:

1. pause merge, release and further distribution of the affected contribution where reasonably possible;
2. preserve commit IDs, diffs, review records, source URLs and relevant metadata; do not republish restricted content;
3. mark affected files or PRs **PROVENANCE-REVIEW** and identify potentially affected dependencies, releases and downstream consumers;
4. restrict access to sensitive evidence and avoid uploading it to additional AI services;
5. establish source lineage, permissions, licence obligations and the scope of any derivative material;
6. seek rights-holder or qualified legal review when necessary;
7. document the decision, remediation, attribution/licence corrections, clean replacement or removal, and remaining uncertainty.

Do not rewrite Git history to erase evidence. Any history correction must be separately justified, authorised and documented; preserve an audit record.

### 10.7 Review gate

A material contribution is not ready to merge while a credible source-origin, permission, licence or clean-room question remains unresolved. Maintainers may request additional provenance, narrow the contribution, require replacement, or decline it. The contributor remains responsible for the certification and evidence supplied.

## 11. Reference framework

These references inform process design; they do not replace the applicable licence, law or project governance:

- [Linux Foundation — Guidance Regarding Use of Generative AI Tools for Open Source Software Development](https://www.linuxfoundation.org/legal/generative-ai)
- [Apache Software Foundation — Generative Tooling Guidance](https://www.apache.org/legal/generative-tooling.html)
- [SLSA — Provenance v1.2](https://slsa.dev/spec/v1.2/provenance)
- [SLSA — Verifying Artifacts](https://slsa.dev/spec/verifying-artifacts)

**Adoption note:** This is a proposed policy until reviewed and merged by the maintainers. A policy document alone does not configure branch protection, CI, access controls, signed attestations or legal enforcement.
