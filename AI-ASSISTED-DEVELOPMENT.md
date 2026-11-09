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

## 9. Related standards

- [Governance](GOVERNANCE.md)
- [Contributing](CONTRIBUTING.md)
- [Evidence and Provenance Method](EVIDENCE-AND-PROVENANCE-METHOD.md)
- [GNU GPL-3.0 licence text](LICENSE)

**Review status:** Proposed. Adopt through maintainer review; do not describe this policy as enforced until controls and contributor acknowledgement are verified.
