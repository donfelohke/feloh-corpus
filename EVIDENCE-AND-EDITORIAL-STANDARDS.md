# Evidence and Editorial Standards

**Status:** LIVE — governing editorial policy  
**Scope:** FELOH Corpus · Gallery catalogue · research reports · datasets · website publications · contributions  
**Also see:** [EVIDENCE-AND-PROVENANCE-METHOD.md](./EVIDENCE-AND-PROVENANCE-METHOD.md) (record types and provenance fields) · [GOVERNANCE.md](./GOVERNANCE.md)

**Governing principle:** Evidence is cited; interpretation is explained; opinion is attributed; uncertainty is visible. No claim receives stronger status than its supporting evidence warrants.

This policy applies to **BLACKS: THE DOCS & DATA** and all corpus research. Thoughts and opinions remain welcome; they must be explicitly attributed and visually distinguished from verified facts.

---

## 1. Mandatory evidence labels

Use these labels in prose, tables, or front-matter. Prefer uppercase short tags in technical notes (`VERIFIED`, `OPINION`) and the long form in public writing where clarity requires it.

| Label | Name | Definition |
|-------|------|------------|
| **VERIFIED** | Verified factual claim | Supported by inspectable evidence appropriate to the claim. Cite the source, relevant passage or dataset, and verification method. |
| **CORROBORATED** | Independently supported claim | Supported by multiple independent sources. Check whether the sources rely on the same original before calling them independent. |
| **DISPUTED** | Contested claim | Credible sources disagree. Present competing claims, evidence and unresolved issues without manufacturing consensus. |
| **UNVERIFIED** | Unconfirmed information | Encountered but not adequately checked. Must not be presented as established fact. |
| **INTERPRETATION** | Analysis or inference | Explicitly reasoned conclusion drawn from evidence. Identify supporting evidence and explain the reasoning. |
| **OPINION** | Personal or attributed viewpoint | Value judgement, belief, preference or argument. Identify whose opinion it is; do not disguise it as objective fact. |
| **TESTIMONY** | First-person account or reported experience | Preserve the speaker's meaning and context. Testimony is evidence of what a person reports or remembers; it does not automatically establish every external factual claim in the account. |
| **PROPOSAL** | Recommendation or future intention | Proposed policy, theory, project or action that has not necessarily been implemented or evaluated. |

**Compatibility with provenance method record types:** SOURCE, FACT, INTERPRETATION, OPINION, HYPOTHESIS, PROPOSAL, DECISION, IMPLEMENTATION, TEST, UNKNOWN remain valid archive record types. Editorial labels above are the **claim-status** layer applied when writing for readers.

---

## 2. How labels appear in documents

### VERIFIED FACT

State the claim, then cite evidence the reader can inspect.

> **VERIFIED:** Eldoret urban centre population was recorded as 475,716 in the 2019 Kenya Population and Housing Census (KNBS / citypopulation.de citing KNBS).

### AUTHOR'S INTERPRETATION

Own the inference; keep evidence inspectable.

> **INTERPRETATION (author):** The documented audience hierarchy prioritises loc-care clients because commercial conversion depends on clear prices and location before brand philosophy.

### ATTRIBUTED OPINION

Name the speaker; preserve context.

> **OPINION (source X):** “…” — [citation].

### UNRESOLVED

State what is missing and what would help.

> **UNVERIFIED / UNRESOLVED:** Local demand for Sisterlocs at the listed starting prices in Eldoret has not been measured from customer data in this repository.

### TESTIMONY

> **TESTIMONY (name or role, date if known):** … — context, consent status, corroboration status.

### PROPOSAL

> **PROPOSAL:** Kiswahili-first default with persistent English toggle (see website PR #27). Not live until merged and verified on Pages.

---

## 3. Non-negotiable research rules

1. **No invention.** Do not invent citations, quotations, dates, statistics, sources or historical details.
2. **Trace to originals.** Prefer primary sources; note when only secondary access is available.
3. **Existence ≠ truth.** A source existing does not establish that every claim inside it is true.
4. **Preserve wording.** Identify paraphrases, translations, edits and AI-assisted transformations.
5. **Retain friction.** Record uncertainty, contradictions, missing evidence and relevant counterevidence.
6. **Oral testimony.** Valuable; document source, context, consent and corroboration status. Do not auto-upgrade memory into VERIFIED external fact.
7. **No status inflation.** Never upgrade opinion, inference, tradition or unverified recollection into VERIFIED merely by repetition.
8. **Corrections.** Record corrections and maintain a review history (PR, date, what changed).

---

## 4. Assessment criteria (source evaluation)

When evaluating a source, record as applicable:

| Criterion | Question |
|-----------|----------|
| **Authority** | Who produced this, and with what competence or mandate? |
| **Accuracy** | Can specific claims be checked against data or primary records? |
| **Purpose** | Why was it published (research, marketing, advocacy, personal)? |
| **Relevance** | Does it actually address the claim under review? |
| **Transparency** | Are methods, limitations and conflicts disclosed? |

---

## 5. Implementation evidence (software and ops)

Aligned with the provenance method:

- A **PROPOSAL** or open PR is not a live system.
- **IMPLEMENTATION** requires repository, branch, PR/commit, paths, tests and, where claimed, deployment verification.
- A merged PR does not by itself prove successful user outcome or current CDN state.

---

## 6. Gallery, corpus and website

| Surface | Application |
|---------|-------------|
| **Corpus research** | Every substantive claim carries a label or equivalent explicit status. |
| **Gallery** | Asset rows require provenance, rights, consent; approval ≠ mere upload. |
| **Website** | Commercial facts (prices, location, services) must match the service catalogue; no invented testimonials. |
| **AI-assisted drafts** | Label AI transformation; human review before VERIFIED or public commercial claims. |

---

## 7. Review checklist (editorial)

- [ ] Claims labelled or clearly statused
- [ ] Citations inspectable (or UNVERIFIED stated)
- [ ] Opinion / interpretation / testimony not mixed into VERIFIED
- [ ] Contradictions retained where material
- [ ] Privacy, consent and rights reviewed
- [ ] Implementation claims link to commits/PRs/deploy checks
- [ ] Corrections linked if superseding prior text

---

## 8. Revision

- **Status:** LIVE — documentation baseline (25 October 2026)
- **Not asserted:** that every historical corpus page has been retro-labelled
- **Change process:** PR on this file; update GOVERNANCE and DOCUMENTATION-TREE when the standard itself changes
