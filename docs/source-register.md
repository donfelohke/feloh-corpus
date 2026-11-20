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


## Technical sources — GNU/MAVERIK, DEVA3 and contemporary XR

| Source ID | Source | Supports | Limits / use |
|---|---|---|---|
| SRC-MAVERIK-001 | Hubbold et al., “GNU/MAVERIK: A microkernel for large-scale virtual environments,” *Presence*, 10(1), 22–34 (2001), https://doi.org/10.1162/105474601750182298 | Historical MAVERIK architecture and application-data callback model | Historical paper; not evidence of current maintenance or modern compatibility |
| SRC-MAVERIK-002 | Howard, Hubbold & Murta, “MAVERIK: A Virtual Reality System for Research and Teaching,” GVE'99, https://diglib.eg.org/server/api/core/bitstreams/6dcfe6df-735f-4db6-96d3-66e37cdbdce9/content | Modular microkernel, spatial/display management, culling, interaction, navigation and device I/O | Historical research description; verify exact release/source separately |
| SRC-MAVERIK-003 | GNU archive index, https://ftp.gnu.org/gnu/maverik/ | Surviving historical release archives | Archive presence does not establish project activity, buildability or licence details of every file |
| SRC-DEVA3-001 | Pettifer, Cook, Marsh & West, “DEVA3: architecture for a large-scale distributed virtual reality system,” ACM VRST 2000, https://doi.org/10.1145/502393.502397 | Distributed VE, synchronization/subjectivity and object-behaviour model | Abstract and bibliographic record; detailed implementation claims require full paper/source |
| SRC-DEVA3-002 | DBLP bibliographic record, https://dblp.org/rec/conf/vrst/PettiferCMW00 | Authors, title, venue and publication metadata | Bibliographic corroboration, not full technical evidence |
| SRC-OPENXR-001 | Khronos OpenXR, https://www.khronos.org/openxr/ | Native XR API standard and ecosystem | API support is not proof of runtime/device/extension support |
| SRC-MONADO-001 | Monado project documentation, https://monado.freedesktop.org/ | Linux OpenXR runtime project and supported architecture | Hardware support is device/driver-specific; qualify exact target |
| SRC-MONADO-002 | Monado developer architecture, https://monado.pages.freedesktop.org/monado/index.html | Internal XRT interfaces and modular runtime components | Developer documentation can lag source; inspect pinned code |

These entries are research sources, not claims that every source has been fully extracted or independently corroborated. The WARENA architecture note records the current bounded synthesis and unresolved source-archaeology work.


## African Sage Philosophy and philosophic sagacity — 2026-11-20

| Source ID | Source | Supports | Limits / use |
|---|---|---|---|
| SRC-SAGE-001 | Stanford Encyclopedia of Philosophy, “African Sage Philosophy,” archived Spring 2026 edition, https://plato.stanford.edu/archives/spr2026/entries/african-sage/ | Oruka project, oral reasoning, Eurocentric bias, literacy, four trends and philosophical criteria | Secondary reference; entry's substantive revision is dated 22 February 2016 |
| SRC-SAGE-002 | Internet Encyclopedia of Philosophy, “African Sage Philosophy,” https://iep.utm.edu/african-sage/ | Project history, Oruka's intellectual setting, folk/philosophic sage distinction, criticisms and later scholarship | Secondary reference; verify primary claims against Oruka's own publications |
| SRC-SAGE-003 | Oruka, H. Odera (ed.), *Sage Philosophy: Indigenous Thinkers and Modern Debate on African Philosophy* (1990) | Primary dialogues and Oruka's presentation of individual sages | Consult exact edition; verify page numbers and quotation context before reuse |
| SRC-SAGE-004 | Azenabor, Godwin, “Odera Oruka’s Philosophic Sagacity: Problems and Challenges of Conversation Method in African Philosophy,” *Thought and Practice* 1(1), 2009, pp. 69–86, https://www.ajol.info/index.php/tp/article/download/46307/32705/0 | Conversation method and methodological challenges | Critical secondary analysis; interpret within wider debate |
| SRC-SAGE-005 | Kazeem, Fayemi Ademola, “H. Odera Oruka and the Question of Methodology in African Philosophy: A Critique,” *Thought and Practice* 4(2), 2012, https://doi.org/10.5840/tap20124211 | Methodological critique and scholarly reception | Secondary article; obtain full text for detailed claims |
| SRC-SAGE-006 | Mosima, Pius Maija, *Philosophic Sagacity and Intercultural Philosophy: Beyond Henry Odera Oruka*, African Studies Centre Leiden, 2016, https://www.ascleiden.nl/publications/philosophic-sagacity-and-intercultural-philosophy-beyond-henry-odera-oruka | Later comparative and intercultural scholarship | Book-level record and abstract; full text review required for detailed interpretation |

These sources are indexed for the Oruka research dossier. Indexing does not imply exhaustive reading of every primary text or complete verification of every claim. Preserve this distinction in future bibliography work.
