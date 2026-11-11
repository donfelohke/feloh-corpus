# COMPUTE + ARTS — Research Programme

**Status:** RESEARCH / proposed programme · **Version:** 0.1 · **Record date:** 2026-10-25

## Purpose and canonical relationship

COMPUTE + ARTS investigates how computational systems can support artistic expression, embodied practice, cultural memory and creative autonomy without displacing human authorship or extracting community-held knowledge. It is a research programme, not a claim that a unified product already exists.

- **FELOH generates:** human authorship, expression and original work.
- **WARENA enables:** inspectable, maintainable, reproducible and local-first computing.
- **IKAI reflects:** participant-directed reflection; a mirror, not a judge.
- **GENJE embodies:** Genge, livecoding, movement, performance and choreohacking.
- **NAKEBUSEN grounds:** craft and livelihood; commercial transactions remain within NAKEBUSEN.

The FELOH Corpus should hold shared research methods, bibliography, claim status and decision provenance. Specialist repositories should hold their domain implementations and working material.

## Research questions

**RQ1 — Authorship.** How should a workflow record human intention, algorithmic rules, AI/tool assistance, edits, samples, collaborators and final selection without misleading authorship claims?

**RQ2 — Culturally grounded tools.** How can artists and cultural custodians shape the problem definition, vocabulary, interface and evaluation rather than being treated merely as training-data sources?

**RQ3 — Reproducible performance.** What minimum record allows another person to inspect and attempt a livecoded or audiovisual performance, while documenting where exact reproduction is impossible or undesirable?

**RQ4 — Embodied interaction.** How can movement-informed interfaces support participant agency without inferring identity, diagnosing people, assigning scores or claiming universal meanings for situated movement?

**RQ5 — Local-first preservation.** Which source files, media, software versions, sample libraries, licences, metadata and environment descriptions are needed to preserve work beyond a platform's lifespan?

**RQ6 — Cultural rights.** What consent, attribution, access, licensing and benefit-sharing process is appropriate before documenting or reusing community-held knowledge or cultural expressions?

**RQ7 — Practical accessibility.** Can a creative workflow run on available GNU/Linux hardware, offline where feasible, with documented setup costs, limitations and fallback paths?

## Boundaries

In scope: literature review; public technical documentation; source-linked claims; approved interviews or oral histories; participant-directed prototypes; reproducibility, privacy, accessibility and rights evaluation.

Not permitted by default: covert recording; face identification; biometric identity matching; diagnosis; person scoring; hidden profiling; scraping private material; publishing restricted cultural knowledge without authority; using cultural materials to train models without documented rights and consent; claiming community endorsement from one person's account; presenting a specification or commit as proof that software works.

## Evidence labels

- **OFFICIAL DOCUMENTATION REVIEWED:** official technical, legal or institutional documentation was examined.
- **PRIMARY SOURCE REVIEWED:** the source itself was examined for the claim.
- **ABSTRACT / DESCRIPTION REVIEWED:** only the landing page, abstract or description was examined.
- **REPORTED FINDING:** attributed to a source, not independently replicated.
- **INTERPRETATION:** reasoned reading, not a direct source claim.
- **HYPOTHESIS:** requires testing.
- **RECOMMENDATION:** proposed action, not an established fact.
- **UNKNOWN / NOT VERIFIED:** evidence is insufficient.
- **LEGAL REVIEW REQUIRED:** currentness and applicability have not been determined.

Official status does not make every source claim universally applicable. A located source is not necessarily fully reviewed.

## Prototype portfolio

### P1 — E-Genge livecoding instrument
**Status: PROPOSED; not implemented by this document.** Evaluate TidalCycles with SuperDirt/SuperCollider on GNU/Linux as one candidate baseline. Measure setup burden, timing/latency, expressive control, offline operation, sample rights, session recovery and artistic fit. Acceptance evidence: tested versions, setup instructions, original rights-cleared patterns, latency method/results, offline test, known limitations and an independent reproduction attempt.

### P2 — FELOH living archive
**Status: PROPOSED.** Record creator/contributors, title, date and uncertainty, source file, checksum where useful, context, transformations, transcription/translation lineage, consent, rights, access level, licence and preservation actions. Preserve originals; represent derivatives as linked records. Acceptance evidence: sample non-sensitive records, export/restore test, rights review, access test and documented restriction/withdrawal process.

### P3 — Movement-informed creative interface
**Status: PROPOSED; not a validated movement-analysis tool.** Begin with opt-in participant-directed movement-to-sound/visual experiments. If sensors are used, document raw signals, derived features, retention, data paths and failure modes. Acceptance evidence: participant explanation and consent, no-recording mode, accessibility review, clear distinction between signal and interpretation, and no identity/diagnostic/scoring outputs.

### P4 — IKAI reflective creative workspace
**Status: PROPOSED; not a released product.** Explore local session notes, project history, user-selected observations and links to source artefacts. Users control retention, export and external processing. Acceptance evidence: offline test, inspectable data model, export/delete/retention tests, threat model, user-controlled reflection prompts and no covert profile.

## Technical and research method

Prefer plain-text Markdown, Git, documented structured data, checksums, immutable originals and SQLite where structured local records are needed. Use Guix/RDE only where actually tested. Record versions, hardware, dependencies, media licences and migration paths. Reproducibility is an attemptable, bounded procedure; it does not guarantee identical audio/visual output across hardware.

For each question:
1. Define scope, date range and inclusion/exclusion criteria.
2. Search primary sources first: legislation, original papers, official documentation, standards and project sources.
3. Log queries, dates, URLs and access limits.
4. Assign source IDs and annotate sources individually.
5. Link each extracted claim to its sources and review status.
6. Seek counterevidence and competing approaches.
7. Separate findings, interpretation, hypotheses and recommendations.
8. Record what was not checked and what could change the conclusion.
9. Audit existing repositories before proposing implementation.
10. Use a branch and PR; run checks and verify the resulting commit and links.

## Repository responsibilities

- FELOH Corpus: shared bibliography, claim ledger, methods, governance and decision provenance.
- GENJE: creative works, performance source, livecoding, movement practice and reproducibility records.
- WARENA: environment definitions, packaging, offline operation, integration and recovery tests.
- IKAI: reflective-interface hypotheses, privacy model and participant-directed experiments.
- Gallery: approved assets with rights/provenance records.
- Public site: reviewed public-facing views, not the canonical research record.

These responsibilities follow current README descriptions; they do not prove every capability or path exists.

## Milestones

- **M0 — Baseline:** inspect bibliography, claim ledger, relevant PRs and specialist repository trees.
- **M1 — Literature:** annotate sources across computational art, livecoding, movement, digital humanities, reproducibility and cultural rights.
- **M2 — Claims:** create bounded claims linked to sources and review states.
- **M3 — Architecture:** document data model, local/offline boundaries, media formats and repository ownership.
- **M4 — Prototype:** select one question and build only after prerequisites and rights are clear.
- **M5 — Evaluation:** test, document failures, obtain review and publish only claims supported by evidence.

## Limitations

This is a research plan and initial evidence map, not a systematic review, legal opinion, community consultation, ethics approval, benchmark or software release. Search coverage is not exhaustive. The bibliography records review depth per source.
