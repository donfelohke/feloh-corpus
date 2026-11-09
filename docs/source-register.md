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


## Movement notation and reflective-computing sources — 2026-11-09

### SRC-REFLECT-2026-001 — Reflective Computing
- **Author:** Md Haseen Akhtar
- **Title:** *Reflective Computing: Seven Dimensions from the Gaps in 134 Interactive Systems, 1996–2026*
- **Type:** Research preprint / critical review
- **Identifier:** arXiv:2610.35696v1 [cs.HC]
- **Submitted:** 2026-10-26
- **URL:** https://arxiv.org/abs/2610.35696
- **PDF:** https://arxiv.org/pdf/2610.35696
- **Accessed:** 2026-11-09
- **Review:** Full 54-page PDF inspected. No independent replication or supplementary-data audit claimed.
- **Use:** IKAI reflective-compute design research; seven dimensions: tempo agency, invitational form, interpretive openness, reflective depth, temporal span, protected idleness and ethical non-extraction.
- **Limitations:** Purposive exemplar set of 134 ACM interactive systems, not an exhaustive census. Reported results are the paper's findings, not independently reproduced facts. Peer-review/publication status is not established by this record.
- **Editorial label:** VERIFIED (bibliographic metadata and paper text inspected); INTERPRETATION (IKAI application); PROPOSAL (prototype/evaluation work).
- **Canonical note:** [Labanotation and Reflective Computing research brief](research/labanotation-and-reflective-computing-2026-11.md).

### SRC-LABAN-WIKI-2026-001 — Labanotation overview
- **Title:** Labanotation
- **Author:** Wikipedia contributors; individual authorship is revision-based
- **Type:** Tertiary encyclopedia / discovery source
- **URL:** https://en.wikipedia.org/wiki/Labanotation
- **Accessed:** 2026-11-09
- **Use:** Initial orientation to historical development and basic notation concepts.
- **Limitations:** Not a primary source or specialist teaching authority. Follow the article's citations and use institutional and specialist sources for technical claims.
- **Editorial label:** DISCOVERY ONLY.
- **Corroboration:** Ohio State University Department of Dance resource page: https://dance.osu.edu/research/dnb/resources

### SRC-LABAN-OSU-2026-001 — Ohio State University Dance Notation resources
- **Institution:** The Ohio State University, Department of Dance
- **Type:** Institutional educational/resource page
- **URL:** https://dance.osu.edu/research/dnb/resources
- **Accessed:** 2026-11-09
- **Use:** Institutional orientation to Labanotation/Kinetography Laban, Motif Description and Laban Movement Analysis; links to specialist bodies and tutorials.
- **Limitations:** Resource overview, not a full notation textbook or independent validation of all applications.
- **Editorial label:** VERIFIED (institutional page inspected); detailed instruction requires specialist sources.

**Terminology caution:** Labanotation/Kinetography Laban, Motif notation, Laban Movement Analysis and Bartenieff Fundamentals are related but distinct. Do not use these names as synonyms.

 
## African movement documentation and further critical sources — 2026-11-09

### SRC-OSEI-2020-001 — Documenting Ghanaian dances through Labanotation
- **Author:** Latipher Amma Osei
- **Year:** 2020
- **Publication:** *African Research Review: An International Multidisciplinary Journal*, 14(2), 112–120
- **DOI:** https://doi.org/10.4314/afrrev.v14i2.11
- **Institutional record:** https://www.uew.edu.gh/theatre-arts/staff/laosei/publications/29001/detail
- **Type:** Scholarly article; institutional publication record and abstract reviewed
- **Use:** Ghanaian dance documentation; challenges of Labanotation; proposed complementarity with cinematography and existing oral/aural/observational practices.
- **Limitations:** Ghana-specific; full article not reviewed in this intake. Do not generalise to all African dance.
- **Editorial label:** CORROBORATED (bibliographic record and abstract); full argument requires article review.

### SRC-AKINSIPE-2015-001 — Development of 'Stick Figure' Notation for African Dances
- **Author:** Felix Akinsipe
- **Year:** 2015
- **Repository:** University of Ilorin Institutional Repository
- **URL:** https://uilspace.unilorin.edu.ng/items/6416499b-c0df-4d9b-91e5-3a7bf42e18f8
- **Type:** Scholarly repository record; abstract reviewed
- **Use:** Alternative notation proposal; timing and direction identified in the abstract as challenges.
- **Limitations:** The abstract is an author's argument, not proof that established notation systems are universally inadequate. Full text has not been critically reviewed; repository lists a very large RTF file.
- **Editorial label:** CORROBORATED (metadata and abstract); PROPOSAL (author's suggested system).

### SRC-BLUM-DNB-2026-001 — Odette Blum, African Dances and Games archive note
- **Contributor:** Mei-Chen Lu, Dance Notation Bureau Theory Bulletin Board
- **Page date:** 2026-09-23
- **URL:** https://www.dancenotation.org/theory-bulletin-board/african-dances-and-games/
- **Type:** Specialist archive / collection note
- **Use:** Discovery of historical Ghanaian dance films and Labanotation records made after Blum's 1966–1968 teaching period at the University of Ghana; examples include Ghana and one Nigerian dance, Agide.
- **Rights:** DNB states the PDF is supplied for educational and research purposes only and may not be shared, reproduced or sold without prior permission from Odette Blum.
- **Limitations:** Archive description, not independent historical verification of every record. Do not republish its PDF, scores or images without permission.
- **Editorial label:** VERIFIED (archive note and stated restriction); historical details should be corroborated with the publication and archive records.

### SRC-GRIM-WONG-2015-001 — Movement Notation and the Analysis of Embodied Knowledge
- **Authors:** Kate Grim-Feinberg and Monica FA Wong Santos
- **Publication:** *Journal for the Anthropological Study of Human Movement*, 22(2)
- **URL:** https://jashm.press.uillinois.edu/22.2/grim-feinberg.html
- **Type:** Scholarly ethnographic methods article; full article reviewed online
- **Use:** Three examples: Lahu Na Shehleh New Year dance, Philippine ballet practice and children's spatial/social practices in Peru. Shows collaborative correction of scores by a Lahu dancer, importance of direct contextual inquiry, and use of video/audio alongside notation.
- **Limitations:** Case studies are not a universal validation of Labanotation; authors describe limitations in their own video-only initial analysis and the need for community expertise.
- **Editorial label:** REVIEWED (full article); case-specific findings only.

### SRC-ICKL-TEXTBOOKS-001 — ICKL bibliography of textbooks
- **Institution:** International Council of Kinetography Laban
- **URL:** https://ickl.org/resources/textbooks/
- **Type:** Specialist bibliography; page states list is in progress
- **Use:** Locate Ann Hutchinson Guest's *Labanotation: The System of Analyzing and Recording Movement* (4th ed., 2005), Albrecht Knust's *A Dictionary of Kinetography Laban* (1997), and other language-specific teaching texts.
- **Limitations:** Bibliography is incomplete and not a substitute for checking editions, availability or rights.
- **Editorial label:** VERIFIED (bibliographic listing); books not yet read.
