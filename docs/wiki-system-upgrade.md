# FELOH Sovereign Wiki System Upgrade

**Status:** PROPOSED  
**Scope:** Documentation architecture for the FELOH Sovereign Corpus  
**Authority:** Subject to review and approval through a pull request  
**Principle:** ONE CORPUS → MANY VIEWS → ONE PRACTICE.

## 1. Purpose

Upgrade the corpus from a collection of Markdown documents into a governed, source-first knowledge system that is navigable, auditable, portable, and suitable for offline preservation. The corpus is the source of record for shared terminology, governance, decisions, specifications, provenance, and implementation status. Specialist repositories may maintain their own implementation details but should link to canonical definitions here.

This document proposes architecture; it does not assert that a generated wiki, search index, automated validation, or deployment already exists.

## 2. System boundaries

1. **Sources:** books, papers, datasets, original works, conversations, repositories, standards, and other traceable materials.
2. **Evidence records:** source metadata, stable identifiers, citations, claim links, access dates where relevant, rights, and limitations.
3. **Research records:** questions, methods, synthesis, counter-evidence, uncertainty, and conclusions.
4. **Canonical records:** approved definitions, governance, architecture, decisions, and specifications.
5. **Publication views:** public website, topic indexes, technical documentation, English and Swahili editions, and offline exports.
6. **Operational evidence:** commits, test results, observations, release manifests, and recovery tests.

Do not collapse these layers. A source is not a conclusion; a conclusion is not canon; a specification is not implementation; a commit is not proof that described behaviour works.

## 3. Proposed information architecture

- `00-START-HERE/`: orientation, navigation, standards, glossary.
- `01-CANON/`: canonical register, brand constitution, codex references, decisions.
- `02-RESEARCH/`: topic register, research questions, literature reviews, annotated bibliography, reports.
- `03-EVIDENCE/`: source register, claim register, datasets, methods, limitations.
- `04-INSTITUTIONS/`: FELOH, NAKEBUSEN, WARENA, IKAI, GENJE.
- `05-DOMAINS/`: research domains and cross-cutting subject indexes.
- `06-TECHNICAL/`: architecture, specifications, operations, security, tests, runbooks.
- `07-PUBLISHING/`: website copy, technical copy, language editions, release records.
- `08-STEWARDSHIP/`: contribution, review, rights, succession, preservation.
- `09-REGISTERS/`: assets, versions, relationships, open questions.
- `10-ARCHIVE/`: manifests, release records, deprecated material.

This is a target architecture, not a claim that all directories exist. Before migration, inventory current files, existing topic registers, repository links, and canonical documents. Preserve history and do not overwrite source material during migration.

## 4. Evidence and status vocabulary

Use evidence labels in page prose where needed:

- **VERIFIED:** directly supported by cited, inspectable evidence within the stated scope.
- **INTERPRETATION:** reasoned inference; explain the reasoning and alternatives.
- **OPINION:** attributed value judgement or personal position.
- **UNVERIFIED:** plausible but not adequately established.
- **DISPUTED:** credible sources conflict; represent the disagreement.
- **UNKNOWN:** the available record does not establish an answer.

Use lifecycle labels for projects and documents: `LIVE`, `PROTOTYPE`, `RESEARCH`, `CONCEPT`, `HISTORICAL`, `SUPERSEDED`, `UNKNOWN`. Do not confuse evidence labels with lifecycle labels. Define the scope of any verification and record contrary evidence or limitations.

## 5. Source and claim traceability

Where practical, maintain stable IDs for sources, claims, decisions, and documents. A claim record should identify:

- Claim ID and concise claim text.
- Claim type and evidence status.
- Supporting and contradicting source IDs.
- Relevant quotation or precise location, with page/section/URL as applicable.
- Author or publisher, publication date, access date where useful, and rights.
- Researcher's interpretation, caveats, and next review question.
- Pages, decisions, or releases that rely on the claim.

Preferred chain:

`SOURCE → CLAIM → SYNTHESIS → DECISION (if any) → IMPLEMENTATION (if any) → TEST / OBSERVATION → RELEASE RECORD`

Not every source results in a claim, and not every research conclusion should become institutional policy.

## 6. Page metadata and template

Use a small, consistent metadata set for substantive pages. Recommended YAML front matter:

```yaml
---
id: RESEARCH-EXAMPLE-001
title: "Descriptive page title"
type: research
status: RESEARCH
evidence_status: UNVERIFIED
language: en
created: YYYY-MM-DD
updated: YYYY-MM-DD
reviewed: null
canonical: false
sources: []
related: []
---
```

Use valid dates when the page is created or updated. Do not invent reviewer identities or dates. `canonical: true` is reserved for a page explicitly approved as canonical. Use stable IDs; do not reuse IDs after a page is retired. The exact schema may be adjusted after auditing existing conventions.

## 7. Publication and privacy boundaries

- Public pages must contain only approved material and lawful, appropriately attributed source content.
- Do not publish private customer records, credentials, secrets, private correspondence, or personal data without a valid basis and explicit approval where required.
- Customer transactions remain within NAKEBUSEN's appropriate operational boundary; the public corpus is not a customer database or booking/payment system.
- Keep internal-only material out of public builds through explicit allowlists or separate source locations. Do not rely only on a hidden navigation link.
- Do not assume that a publicly accessible source is free to reproduce. Record licence, copyright, attribution, and excerpt constraints.
- The English edition is the default global edition; provide a persistent Swahili language switch in the public interface when implemented. Translation differences must be reviewable and must not silently change canonical meaning.
- Prefer plain Markdown, local assets where approved, generated static output, and graceful offline access. Avoid requiring a remote runtime for core reading.

## 8. Git and review workflow

1. Inspect existing files and repository state before edits.
2. Make focused changes on a feature branch; do not commit directly to `main` for substantive changes.
3. Open a pull request with scope, rationale, files changed, risk, evidence, and test results.
4. Validate links, required metadata, source references, language links, and public/private boundaries.
5. Review generated output on mobile and desktop before publishing.
6. Merge only after review and applicable checks; record unresolved limitations.
7. Tag or manifest releases and preserve previous records.
8. Correct mistakes through traceable edits; do not erase historical decisions without a superseding record.

## 9. Validation roadmap

**Stage A — inventory:** enumerate current files, headings, links, front matter, duplicate topics, licences, and existing workflows.

**Stage B — schema:** settle IDs, page types, lifecycle/evidence vocabularies, source/claim fields, and canonical authority rules.

**Stage C — baseline checks:** broken internal links, missing required metadata, invalid dates, duplicate IDs, missing source references, and prohibited sensitive files.

**Stage D — build and search:** generate a static index from approved Markdown, provide local search, and retain a plain-Markdown fallback.

**Stage E — publication:** validate allowlisted public content, English/Swahili navigation, keyboard access, responsive layouts, and offline behaviour.

**Stage F — preservation:** generate release manifest and checksums; document export, backup, and restoration; test recovery instead of merely documenting a plan.

Do not report a stage as complete until its artifacts and results have been checked.

## 10. Acceptance criteria

- Existing canonical documents and topic registers are inventoried before migration.
- Every migrated page retains provenance and useful Git history where practical.
- Research claims can be traced to sources and limitations.
- Proposed content is distinguishable from approved canon.
- Internal links and stable IDs are checked automatically or through a documented manual review.
- Public builds exclude private and unapproved content by construction.
- The corpus remains readable as plain Markdown without a proprietary service.
- Publication and recovery claims have reproducible evidence.
- Stewardship procedures support contributors and succession, not permanent single-person control.

## 11. Open decisions

- Which existing source directories and topic registers should be migrated first?
- Which static-site generator, if any, best fits current GitHub Pages workflows and offline requirements?
- Should internal-only research live in a separate private repository rather than the public corpus?
- What exact source and claim metadata are practical for the first release?
- Which licences apply separately to software, documentation, research notes, and curated assets?

Resolve these through inspection and recorded decisions, not assumptions.
