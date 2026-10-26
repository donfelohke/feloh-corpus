# Institutional Documentation Framework

**Status:** PROPOSED — review required  
**Scope:** FELOH Sovereign Corpus and the related public repositories  
**Canonical home:** `feloh-corpus`  
**Review basis:** Repository documentation inspected on 25 October 2026  
**Purpose:** Define a durable, auditable documentation practice without claiming that unverified institutional controls are already operating.

## 1. Purpose and boundary

This framework defines how institutional knowledge, decisions, evidence, responsibilities, operational procedures, and publication records should be documented across the FELOH ecosystem.

It complements, and does not replace:

- [Repository governance](../GOVERNANCE.md)
- [Contributing rules](../CONTRIBUTING.md)
- [Evidence and editorial standards](../EVIDENCE-AND-EDITORIAL-STANDARDS.md)
- [Evidence and provenance method](../EVIDENCE-AND-PROVENANCE-METHOD.md)
- [Decision and provenance protocol](decision-provenance.md)
- [Documentation tree](../DOCUMENTATION-TREE.md)
- [Succession and stewardship](succession.md)
- [Master topic register](MASTER-TOPIC-REGISTER.md)

**Institutional documentation is a record of what is known, decided, assigned, performed, and verified. It is not a substitute for the underlying evidence or for the authority to make a decision.**

The governing principle remains: **ONE CORPUS → MANY VIEWS → ONE PRACTICE.**

## 2. Institutional record classes

Use the smallest record type that preserves the necessary context. Do not create a second canonical source for a fact already maintained elsewhere.

| Record class | Purpose | Minimum evidence or fields |
|---|---|---|
| Policy / standard | States a rule or required practice | Scope, normative language, authority/status, effective date, review trigger |
| Decision record | Captures a material choice | Question, options, rationale, decision status, evidence, consequences, supersession |
| Research record | Preserves a question and findings | Question, method, sources, dates, findings, limitations, open questions |
| Claim record | Links a factual assertion to support | Claim text, evidence label, source reference, locator, counter-evidence, reviewer/status |
| Source record | Describes a source item | Creator, title, date, source type, stable locator, access date, rights, reliability notes |
| Operational runbook | Describes a repeatable task | Preconditions, permissions, steps, expected result, failure path, rollback, verification |
| System specification | Describes intended or observed behaviour | Requirements, interfaces, dependencies, constraints, maturity label, tests/evidence |
| Incident / exception record | Preserves a failure or deviation | Date, impact, observed facts, response, unresolved risks, corrective actions |
| Release / publication record | Records what was released | Version/commit, scope, checks, known limitations, approval, publication location |
| Asset / rights record | Tracks media and reuse authority | Asset ID, provenance, creator if known, licence/permission, consent limits, publication status |
| Role / handover record | Supports continuity | Role purpose, responsibilities, access boundaries, current holder if confirmed, handover status |
| Meeting / consultation record | Preserves institutional discussion | Date, participants where appropriate, agenda, attributed positions, decisions and follow-up |

These record classes are a proposed standard. Their presence in this document does not mean a register, committee, incident process, or approval workflow already exists.

## 3. Source-of-truth rules

1. Maintain each shared fact in one canonical location. Other repositories and websites should link to it or identify their local implementation-specific details.
2. Use `DOCUMENTATION-TREE.md` for repository and document ownership; use `docs/README.md` as the navigational index.
3. Use the [Master Topic Register](MASTER-TOPIC-REGISTER.md) for subject coverage, not as evidence that every topic has been researched.
4. Use the [bibliography and source inventory](../research/README.md) for source discovery and provenance; use claim-level citations for material factual assertions.
5. Use the [decision and provenance protocol](decision-provenance.md) when a change affects canonical meaning, policy, responsibility, status, or project boundaries.
6. Keep operational implementation details in the responsible specialist repository. Link to the canonical policy rather than copying and independently editing it.
7. When two records conflict, preserve the conflict, mark the affected claim **DISPUTED** or **UNKNOWN** as appropriate, and create a reviewable resolution proposal. Do not silently overwrite history.

### Domain ownership

| Domain | Canonical location / responsible view |
|---|---|
| Shared terminology, ecosystem boundaries, evidence policy | `feloh-corpus` |
| Public website content and deployed behaviour | `donfelohke.github.io` and its verified deployment records |
| Beauty service catalogue and customer operations | `NAKEBUSEN` |
| Systems engineering, infrastructure and recovery | `WARENA` |
| Reflective-compute research and prototypes | `Ikai` |
| Creative technology, performance and embodied practice | `Genje` |
| Approved visual assets and rights metadata | `Gallery` |
| Authored research and corpus source inventory | `feloh-corpus`, with originals preserved and attributed |

Repository names identify intended responsibility; they do not prove that every repository is complete, current, or operational.

## 4. Evidence, status and attribution

Use the evidence labels defined in [Evidence and Editorial Standards](../EVIDENCE-AND-EDITORIAL-STANDARDS.md). At minimum, distinguish:

- **VERIFIED / CORROBORATED:** supported by the recorded evidence at the stated scope.
- **DISPUTED:** credible evidence conflicts or the interpretation remains contested.
- **UNVERIFIED / UNKNOWN:** evidence is insufficient or has not been checked.
- **INTERPRETATION / OPINION:** an attributed analysis or viewpoint, not presented as an established fact.
- **TESTIMONY:** a person's account, attributed and contextualised without treating it as universal proof.
- **PROPOSAL:** a suggested future state, not an adopted rule or deployed capability.

For material claims, preserve the source locator and enough context for another contributor to check it. Record access dates for changing web pages and statistics. Distinguish a source's own statement from an independent confirmation.

For every implementation claim, cite the relevant code, commit, test result, deployment observation, or operational record. A plan, specification, successful file write, or merged documentation change does not by itself prove runtime behaviour.

## 5. Lifecycle and change control

Use this lifecycle where appropriate:

1. **Capture:** record the source, question, decision, incident, or requirement without silently rewriting the original.
2. **Classify:** choose a record class, owner domain, status, sensitivity, and intended audience.
3. **Validate:** check sources, rights, privacy, internal consistency, and relevant counter-evidence.
4. **Review:** propose substantive changes through a focused branch and pull request where supported.
5. **Accept:** mark a proposal as adopted only after the applicable review/decision has actually occurred.
6. **Publish or operationalise:** publish the approved view or execute the approved procedure.
7. **Verify:** record observable results and limitations; do not infer success from intention.
8. **Maintain:** review on a trigger, after a material change, or on a stated review date.
9. **Supersede or archive:** preserve lineage and explain what replaced the record. Do not erase the historical record without a documented reason.

Recommended review triggers include changed law or policy, changed service prices, changed system behaviour, new contradictory evidence, a security incident, a change of maintainer, or a release that invalidates prior instructions.

## 6. Minimum document header

Use this header for substantial institutional documents where applicable:

```markdown
# Document title

- **Record ID:** (stable ID or UNKNOWN)
- **Status:** PROPOSED | LIVE | RESEARCH | HISTORICAL | SUPERSEDED | UNKNOWN
- **Scope:** (what this covers and excludes)
- **Canonical owner:** (repository/path or UNKNOWN)
- **Author / contributor:** (attributed where known)
- **Created:** YYYY-MM-DD or UNKNOWN
- **Last reviewed:** YYYY-MM-DD or NOT REVIEWED
- **Evidence:** (source, commit, test, or observation links)
- **Supersedes / superseded by:** (record references or NONE RECORDED)

## Purpose

## Evidence and method

## Findings / requirements / decision

## Limitations and open questions

## Change history
```

Do not invent record IDs, authors, approval dates, reviewers, or review events. Use `UNKNOWN`, `NOT REVIEWED`, or `NONE RECORDED` where appropriate.

## 7. Privacy, rights and access

- Publish only material suitable for the intended audience and supported by the necessary rights or permission.
- Do not commit credentials, access tokens, private customer records, private correspondence, or unnecessary personal data.
- Obtain appropriate consent before publishing identifiable testimony, sensitive community knowledge, portraits, recordings, or client material.
- Record licence and reuse conditions for third-party material. Repository licensing does not automatically grant rights to content whose rights belong to someone else.
- Keep restricted operational information out of public documentation; document where an authorised private record is maintained only when doing so is safe.
- Respect community authority and limits on Indigenous knowledge. Public availability does not by itself establish consent for every reuse.
- For IKAI, retain the stated design boundary: mirror, not judge; no face identification, diagnosis, scoring, covert surveillance, or hidden profiling.
- Preserve original works and provenance; edits, translations, summaries, and AI-assisted transformations should be identifiable as such.

## 8. Institutional registers to maintain

Create or maintain these registers only when there is a real operational need and a responsible maintainer:

- **Document register:** canonical path, record class, status, owner domain, last review, supersession.
- **Decision register:** decision ID, status, date, affected domains, evidence, review link.
- **Claim ledger:** claim ID, claim text, evidence label, sources, counter-evidence, review status.
- **Source inventory / bibliography:** source metadata, locator, rights, reliability and access notes.
- **System and service register:** component/service, responsible repository, maturity, dependencies, verification evidence.
- **Asset and rights register:** asset identity, provenance, licence/consent, approved use, publication status.
- **Risk / incident register:** observed risk or event, impact, response, owner if assigned, residual uncertainty.
- **Release register:** release or publication identifier, commit, checks, approvals, known limitations.
- **Role and handover register:** documented responsibilities and continuity status; do not imply an appointment without evidence.

Do not duplicate the existing source inventory, master bibliography, claim ledger, topic register, or decision protocol. Extend the existing register when it already serves the same purpose.

## 9. Institutional assurance checklist

Before marking a control or process as operational, record evidence for the applicable items:

- [ ] Canonical owner and scope are defined.
- [ ] Required source and provenance fields are present.
- [ ] Privacy, consent, licensing and access risks are considered.
- [ ] The proposed change is reviewed under the applicable process.
- [ ] Required automated checks ran and their results are linked.
- [ ] Deployment or operational behaviour was observed where relevant.
- [ ] Rollback, correction or supersession path is documented where needed.
- [ ] The index and affected cross-references are updated.
- [ ] The current status, date and known limitations are explicit.

An unchecked item means **not yet evidenced**, not necessarily that the control is absent. Record verified absence separately from an unperformed check.

## 10. Current status and next steps

This framework is **PROPOSED** until reviewed and accepted through the repository's normal change process. The repository already contains governance, contributor guidance, evidence standards, provenance methods, a documentation tree, a master topic register, a bibliography scaffold, a claim ledger, a source inventory, and succession documentation. This framework connects those existing pieces; it does not certify that all associated processes or technical controls are operational.

Recommended follow-up:

1. Review this framework against existing governance and evidence policies; resolve duplication before acceptance.
2. Add only the necessary links to the documentation index and tree.
3. Audit the existing registers for coverage and missing metadata.
4. Verify repository protections, required checks, and publication controls independently before describing them as enforced.
5. Assign maintainers or review responsibilities only through an explicit, recorded decision.
6. Revisit the framework after the first real documentation review cycle and update it based on observed gaps.

**Institutional standard:** preserve the source; cite the claim; attribute the interpretation; record the decision; verify the implementation; retain the history.
