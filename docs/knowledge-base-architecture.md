# Cross-Domain Knowledge Base Architecture

**Status:** PROPOSAL — documentation architecture  
**Owner / authoring identity:** Felix Lwova · Don Feloh · @donfelohke  
**Canonical home:** FELOH Sovereign Corpus  
**Public umbrella:** NAKEBUSEN · LOCS & DIGITAL · Powered by WARENA  
**Review date:** 2026-10-26

## Purpose

Build one maintainable knowledge base across beauty craft, digital services, systems engineering, research, culture, creative computing, business operations, and institutional memory. It must support practical work without flattening different disciplines into one vocabulary or treating every note as fact.

**Operating principle:** ONE CORPUS → MANY VIEWS → ONE PRACTICE.

The corpus is the source of record for shared definitions, cross-domain relationships, evidence standards, decisions, and provenance. Specialist repositories remain the home for domain-specific implementation and working material. Public websites are audience-facing views, not the full knowledge base.

## Information architecture

### Layer A — Canon and governance

- Brand and identity constitution
- Glossary and controlled vocabulary
- Evidence and editorial standards
- Decision records and provenance
- Privacy, rights, consent, security, and stewardship policies
- Repository and source-of-record map

### Layer B — Domain knowledge

- **NAKEBUSEN LOCS:** loc care, beauty craft, consultations, service methods, aftercare, hygiene, service quality, pricing approvals, customer-facing copy, and operating procedures.
- **NAKEBUSEN DIGITAL:** client needs, service catalogue, discovery, scoping, quotations, support boundaries, delivery records, handover, and service quality.
- **WARENA:** GNU/Linux, GNU Guix/RDE research, systems administration, networking, reproducible environments, software supply chains, deployment, backup, restoration, security, and local-first infrastructure.
- **IKAI:** reflective-compute research, hypotheses, protocols, data minimisation, consent, evaluation, limitations, prototypes, and research ethics.
- **GENJE / FELOH:** Genge, live coding, Algorave, choreohacking, sound, movement, creative code, cultural context, authorship, licensing, performance documentation, and practice-based research.
- **Business and livelihoods:** audience research, offers, pricing rationale, marketing experiments, operations, risk, finance concepts, and decision records. Private customer and payment records do not belong in this public repository.
- **Cross-domain research:** history, African and Black life documentation, philosophy, science and technology, political economy, education, institutions, and futures. Each research area must have its own scope, bibliography, evidence map, and uncertainty notes.

### Layer C — Evidence and source records

Store or link to sources, claim records, annotated bibliographies, datasets, interviews or testimony where consent permits, experiment logs, test output, screenshots or observations where appropriate, and corrections. Preserve originals separately from summaries and interpretation.

### Layer D — Practice and implementation

Store working procedures, service checklists, runbooks, reproducible configurations, source code, test plans, operational observations, handover instructions, and release evidence in the relevant specialist repository. Link each implementation back to its requirement or decision.

### Layer E — Audience views

Produce focused views for clients, learners, collaborators, technical operators, researchers, and the public. Views may simplify presentation, but must not change the underlying claim, status, source, price, limitation, or decision.

## Required record fields

Every substantive knowledge entry should include:

- Stable ID or path
- Title and domain
- Record type: SOURCE, FACT, INTERPRETATION, OPINION, HYPOTHESIS, PROPOSAL, DECISION, IMPLEMENTATION, TEST, or UNKNOWN
- Claim status / maturity label
- Summary and intended use
- Author or source attribution
- Source citations and retrieval/publication dates when available
- Method or reasoning
- Related domains, records, decisions, and repository paths
- Limitations, contradictions, and open questions
- Rights, privacy, consent, and publication constraints
- Last-reviewed date and change history where material

Use the [knowledge-entry template](../templates/knowledge-entry.md) as a starting point. Do not require every field for a brief note; mark missing material as unknown rather than inventing it.

## Evidence and status rules

Use the editorial labels in [Evidence and Editorial Standards](../EVIDENCE-AND-EDITORIAL-STANDARDS.md): VERIFIED, CORROBORATED, DISPUTED, UNVERIFIED, INTERPRETATION, OPINION, TESTIMONY, and PROPOSAL.

Use maturity labels in the [glossary](glossary.md): LIVE, PROTOTYPE, RESEARCH, CONCEPT, HISTORICAL, SUPERSEDED, and UNKNOWN. These are different from editorial claim labels; do not mix the two layers.

**Never infer that:**
- a concept is implemented;
- a written procedure has been executed;
- a test plan has passed;
- a successful CI check proves real-world behaviour;
- a public listing proves current availability;
- a source is independent merely because it repeats another source;
- a committed asset is cleared for publication;
- a research prototype is a released product.

## Cross-domain linking

Use links rather than duplicating canonical definitions. When a concept is reused in another domain, add a short domain-specific explanation and link to the canonical entry. If definitions conflict, preserve the conflict and open a decision record; do not silently choose one.

Recommended relationship types: depends_on, supports, implements, tests, contradicts, supersedes, derived_from, used_by, related_to.

## Research workflow

1. Define the question, scope, intended use, and exclusions.
2. Search the corpus and relevant specialist repository before creating a duplicate.
3. Collect primary sources first where available; record provenance and access dates.
4. Extract claims into a claim/source matrix; distinguish evidence from interpretation and opinion.
5. Record disagreement, source limitations, missing data, and confidence rationale.
6. Translate supported findings into a decision, practice, experiment, or clearly labelled open question.
7. Review privacy, consent, rights, security, and publication suitability.
8. Submit substantive changes through a focused branch and pull request.
9. Run relevant checks and inspect the resulting diff.
10. Update the index and record implementation or deployment evidence separately.

## Publication and privacy boundaries

The corpus may document how a business works, but must not become a customer database. Never commit customer names, phone numbers, appointment histories, payment references, private messages, credentials, or sensitive personal records. Public contact information and current offers require approval and re-verification before publication.

For IKAI, preserve the stated boundary: mirror, not judge. Do not add face identification, person scoring, diagnosis, covert surveillance, or hidden profiling.

## Acceptance criteria

This architecture is **PROPOSED** until reviewed. A working knowledge-base release should demonstrate:

- all domains have a named purpose and source-of-record location;
- each new substantive entry uses consistent metadata and evidence labels;
- the documentation index links to the canonical policies and templates;
- internal links and required-file checks pass;
- specialist repositories link back to canonical definitions where relevant;
- no private customer records or secrets are introduced;
- completion claims are supported by actual commit, check, and review evidence.

## Initial implementation order

1. Approve the domain map and knowledge-entry template.
2. Build the source register and annotated bibliography by research question.
3. Prioritise NAKEBUSEN public service facts and operational procedures for current accuracy.
4. Document NAKEBUSEN DIGITAL service scope and delivery/handover evidence.
5. Build WARENA technical runbooks around tested systems rather than proposed configurations.
6. Keep IKAI research protocols and prototype evidence separate from product claims.
7. Build GENJE/FELOH creative-work records with authorship, licence, and cultural context.
8. Add cross-domain learning paths only after the source lists and prerequisites are checked.
