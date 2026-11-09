# Source Register and Research Intake

**Status:** PROPOSAL — source-management baseline  
**Purpose:** Make cross-domain research traceable, reviewable, and useful in practice.

The register indexes sources and the claims they support. It is not a bibliography by itself and must not be used to imply that a source has been read or verified when it has not.

## Source record fields

Create one record per source or stable source collection. Include as many fields as apply:

- **Source ID:** stable ID such as SRC-0001
- **Title:**
- **Author / institution:**
- **Source type:** primary document, dataset, law/policy, academic article, book, technical documentation, interview/testimony, repository, media report, or other
- **Publication / version date:**
- **URL or repository path:**
- **Accessed / retrieved date:**
- **Original language:**
- **Domain and research question:**
- **Primary or secondary source:** explain where unclear
- **Claims supported:** link to claim records or exact document sections
- **Method / scope:**
- **Limitations / conflicts:**
- **Rights, licence, privacy, and consent:**
- **Editorial label:** VERIFIED, CORROBORATED, DISPUTED, UNVERIFIED, INTERPRETATION, OPINION, TESTIMONY, or PROPOSAL as appropriate
- **Review status:** unread, queued, read, extracted, checked, superseded
- **Notes / next action:**

Do not invent missing authors, dates, page numbers, URLs, or source characteristics. Use UNKNOWN where needed.

## Source quality checks

1. Prefer primary sources for direct claims about laws, policy, datasets, project behaviour, official specifications, and original testimony.
2. Use secondary sources to contextualise, interpret, or locate primary evidence.
3. Check publication date, version, scope, method, funding or conflicts where relevant, and whether the source is still current.
4. When multiple sources agree, check whether they are genuinely independent or repeat the same upstream claim.
5. Preserve credible disagreement and contradictory findings.
6. Distinguish what a source directly states from what the researcher infers.
7. Record the exact passage, table, dataset field, commit, test output, or observation that supports a material claim.
8. For web sources, record the access date because content can change.
9. For software, record version, commit, environment, commands, expected result, actual result, and limitations where relevant.
10. Review copyright, licence, privacy, consent, and publication suitability before copying or republishing material.

## Claim-to-source matrix

Use a matrix for research questions with multiple claims:

| Claim ID | Claim (concise) | Editorial label | Supporting sources | Contradicting sources | Method / rationale | Confidence and limits | Next check |
|---|---|---|---|---|---|---|---|
| CLM-0001 | Replace with a specific, testable claim | UNVERIFIED | SRC-0001 | UNKNOWN | State how claim will be checked | State limits | Name next action |

Do not leave example IDs in a published research report as if they were real findings.

## Research intake checklist

- [ ] State the question, scope, intended use, audience, and exclusions.
- [ ] Search existing corpus entries and specialist repositories.
- [ ] Find primary sources and reliable context sources.
- [ ] Record source metadata before summarising.
- [ ] Extract claims with precise citations.
- [ ] Label fact, interpretation, opinion, testimony, hypothesis, and proposal separately.
- [ ] Check contradictions, missing evidence, and source independence.
- [ ] Review privacy, consent, rights, and publication limits.
- [ ] Write a bounded conclusion with uncertainty and further work.
- [ ] Link resulting decisions, experiments, or implementations to evidence.
- [ ] Update the documentation index when the record is intended for ongoing use.

## Domain-specific notes

- **NAKEBUSEN LOCS:** distinguish owner-approved service facts and lived craft knowledge from general health/safety guidance or claims about outcomes. Do not invent client testimonials or credentials.
- **NAKEBUSEN DIGITAL / WARENA:** record exact versions, device/hardware assumptions, commands, network topology where safe, test outcomes, failure modes, and restoration evidence. Redact secrets and sensitive client details.
- **IKAI:** document research questions, consent, data minimisation, processing location, retention, evaluation criteria, and limitations before collecting data.
- **GENJE / FELOH:** record authorship, collaborators, cultural context, source files, licences, samples, and performance conditions.
- **History, politics, culture, and Black life documentation:** distinguish primary records, testimony, quantitative evidence, scholarly interpretation, and opinion. Preserve historical context and disagreement; avoid presenting one source or one voice as universal.

## Status

This register defines a proposed process. It does not assert that any complete source inventory or annotated bibliography has already been compiled.


## Curated foundational sources — 2026-11-09

These are initial source records, not a claim that every linked book, chapter, or resource has been exhaustively read.

### SRC-FOUND-ALG-001 — Algorave general guidelines
- **Author / institution:** Algorave community contributors
- **Type:** Community-sourced guidance in a public repository
- **Version / date:** master branch; no publication date established from the reviewed page
- **URL:** https://github.com/Algorave/guidelines/blob/master/README_en.md
- **Accessed:** 2026-11-09
- **Domain:** GENJE / FELOH creative computing and live-coding practice
- **Use:** Community norms, artistic process visibility, diversity, accessibility, safety and local community building.
- **Limitations:** Not a legal standard, complete history or mandatory event specification. The source invites adaptation.
- **Editorial label:** VERIFIED (page content); INTERPRETATION (local application).
- **Review status:** Read (English README); further review of linked code of conduct and community resources remains open.

### SRC-FOUND-UNESCO-GHA-001 — UNESCO General History of Africa
- **Author / institution:** UNESCO; International Scientific Committee and contributing historians/specialists
- **Type:** Institutional scholarly collection / publication portal
- **Version / date:** Multi-volume collection; portal accessed 2026-11-09
- **URL:** https://www.unesco.org/en/general-history-africa
- **Accessed:** 2026-11-09
- **Domain:** African history, historiography, knowledge systems and cultural context
- **Use:** Locate relevant volumes, methodologies, bibliographies and period/region-specific scholarship.
- **Limitations:** Portal summaries are not substitutes for volume-level evidence or regional and community-specific scholarship. Cite exact volumes and pages for substantive historical claims.
- **Editorial label:** VERIFIED (collection metadata and portal description); individual historical claims require independent volume-level review.
- **Review status:** Read (collection portal); volumes not yet systematically reviewed.

### SRC-FOUND-TYCS-001 — Teach Yourself Computer Science
- **Author / institution:** TeachYourselfCS contributors; site attribution to be checked for formal citation
- **Type:** Curated educational guide / bibliography
- **Version / date:** Site states extensive update in May 2020
- **URL:** https://teachyourselfcs.com/
- **Accessed:** 2026-11-09
- **Domain:** Computer science education / WARENA learning architecture
- **Use:** Nine-subject foundation map: programming, architecture, algorithms/data structures, CS mathematics, operating systems, networking, databases, languages/compilers and distributed systems.
- **Limitations:** Not a live course catalogue or credential. Recheck editions, course versions, availability and learner prerequisites. The guide is aimed at programmers seeking deeper CS foundations.
- **Editorial label:** VERIFIED (site's stated syllabus and recommendations); PROPOSAL (local curriculum adoption).
- **Review status:** Read (main page and subject overview); individual books/courses not yet validated or completed.

Link to the Foundational Reference Map (foundational-reference-map-2026-11.md) for the cross-domain interpretation and application boundaries.
