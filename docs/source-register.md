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

## Agentic operating systems and GNU Hurd — 2026-11-20

| Source ID | Source | Supports | Limits / use |
|---|---|---|---|
| SRC-AGENTOS-001 | Zhao et al., “AgenticOS: An Intent-Oriented Secure Operating System Architecture for Autonomous AI Agents” (2026), https://arxiv.org/abs/2606.15419 | Intent-oriented security architecture proposal for autonomous agents | Research proposal; inspect full paper, threat model and evaluation before adopting mechanisms |
| SRC-AGENTOS-002 | Li et al., “Ring-0 by Default: Agents as Operating Systems (AaOS)” (2026), https://arxiv.org/abs/2610.23199 | Analysis of OS-like responsibilities and security gaps in agent systems | Source-specific taxonomy and counts; not a universal measurement or proof of all agents' behaviour |
| SRC-HURD-AGENT-001 | GNU Hurd project, https://www.gnu.org/software/hurd/ | Official project scope, architecture and development entry point | Project landing page; consult versioned manuals and source for mechanism-level claims |
| SRC-HURD-AGENT-002 | GNU Hurd documentation, https://www.gnu.org/software/hurd/doc/ | User-space servers, translators and system documentation | Documentation version and current implementation must be checked |
| SRC-MACH-AGENT-001 | GNU Mach documentation, https://www.gnu.org/software/hurd/microkernel/mach/ | Mach tasks, ports and IPC concepts | Do not infer a complete revocable object-capability model from port rights alone |
| SRC-GUIX-HURD-001 | GNU Guix, https://guix.gnu.org/ | Guix packaging and system-management project | Hurd support and package coverage are time-sensitive; record exact revision and current test output |

The WARENA [Agentic Operating Environment & GNU Hurd Research specification](https://github.com/donfelohke/WARENA/blob/main/docs/AGENTIC-OPERATING-ENVIRONMENT-GNU-HURD-RESEARCH-2026-11-20.md) is the current synthesis. These entries are source pointers; each technical claim still requires exact version, passage, experiment or source inspection before being marked VERIFIED.
## Movement notation and reflective-computing sources — 2026-11-09

### SRC-REFLECT-2026-001 — Reflective Computing
- **Author:** Md Haseen Akhtar
- **Title:** *Reflective Computing* (subtitle: *Seven Dimensions from the Gaps in 134 Interactive Systems, 1996–2026*)
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


## UNESCO General History of Africa — 2026-11-21

### SRC-UNESCO-GHA-2026-001 — General History of Africa
- **Institution:** UNESCO
- **Type:** Institutional scholarly collection / research and educational resource
- **URL:** https://www.unesco.org/en/general-history-africa
- **Initiative launched:** 1964
- **Collection:** Volumes I–XI; UNESCO's current collection page describes collaboration among more than 550 historians and specialists and an International Scientific Committee with two-thirds African membership.
- **Accessed:** 2026-11-21
- **Use:** Continental historiography, source discovery, research methodology and curriculum design for BEFORE AFRICA.
- **Limitations:** A continental synthesis does not settle local Turkana, Ateker, linguistic, archaeological or oral-history questions. Inspect individual volumes and chapters; corroborate claims with specialist and community-grounded sources.
- **Rights:** Link to official records; check item-level terms before reproducing chapters, illustrations, maps or teaching materials.
- **Editorial label:** VERIFIED (institutional collection metadata); chapter-level claims require direct reading and claim-specific citations.



## BLACK HINTERLAND — BEFORE AFRICA and contemporary Africa baseline — 2026-11-22

| Source ID | Source | Supports | Limits / use |
|---|---|---|---|
| SRC-BH-UNESCO-001 | UNESCO, General History of Africa, Volumes I–XI: https://www.unesco.org/en/general-history-africa | African historiography, prehistory, ancient and modern regional histories, Global Africa and diaspora | Collection-level source; cite individual volume/chapter/page for substantive claims. |
| SRC-BH-WPP-001 | UN DESA Population Division, World Population Prospects 2024: https://population.un.org/wpp/ | Official population estimates and projections to 2100 | State release, geography, scenario and reference year; projections are not census counts. |
| SRC-BH-AFDB-001 | African Development Bank, Africa’s Macroeconomic Performance and Outlook, November 2026: https://www.afdb.org/en/documents/africas-macroeconomic-performance-outlook-november-98553 | Latest dated continental macroeconomic forecast; November update projects 4.6% growth in 2026 and 4.5% in 2027 | Forecast, not final outturn; country and regional outcomes differ. Prefer this revision over May 2026 forecast. |
| SRC-BH-ITU-001 | ITU, Facts and Figures 2026: https://www.itu.int/itu-d/reports/statistics/facts-figures-2026/ | Internet use and digital development indicators; 2026 regional figure for Africa is 42% | ITU region definitions; distinguish use, coverage, affordability, quality and access. |
| SRC-BH-AU-001 | African Union, official portal: https://au.int/ | AU institutions, policy and continental governance | Official institutional source; policy statements do not prove implementation. |
| SRC-BH-A2063-001 | AU/AUDA-NEPAD, Agenda 2063 Second Ten-Year Implementation Plan 2024–2033: https://a2063.africa/publications/second-ten-year-implementation-plan-2024-to-2033 | Current Agenda 2063 delivery framework and seven Moonshots | Aspirations and implementation framework; evaluate outcomes independently. |
| SRC-BH-KEN-001 | Constitution of Kenya (2010), Parliament-hosted PDF: https://www.parliament.go.ke/sites/default/files/2017-05/The_Constitution_of_Kenya_2010.pdf | Constitutional text on sovereignty, language, culture, land, community land, rights and devolution | Primary legal text; interpret with case law, legislation and current institutional practice. |
| SRC-BH-KNBS-001 | Kenya National Bureau of Statistics: https://www.knbs.or.ke/ | Kenyan census, labour, economic and social statistics | Use the specific release, table, reference period and definitions. |
| SRC-BH-MAGICALKENYA-001 | Magical Kenya: https://magicalkenya.com/ | Official tourism-facing heritage and national representation | Promotional source; not independent historical or archaeological authority. |
| SRC-BH-WIKI-001 | Wikipedia, Kenya: https://en.wikipedia.org/wiki/Kenya | Preliminary orientation and bibliography discovery | Tertiary source only; verify substantive claims against primary and specialist sources. |

The canonical research framework is [BLACK HINTERLAND — BEFORE AFRICA](BLACK-HINTERLAND-BEFORE-AFRICA-MASTER-DOSSIER-2026-11-22.md). These entries identify sources for use; they do not claim exhaustive reading, independent replication or community approval. For current indicators, capture the source file, table number, download/access date and exact geography before publishing a number.


## Omarchy, Quickshell, Omaxian and Guix desktop architecture — 2026-11-22

### SRC-OMARCHY-RELEASE-2026-001 — Omarchy v4.5.0 release
- **Project:** Omarchy / omacom
- **Release:** v4.5.0, published 2026-11-05
- **URL:** https://github.com/omacom/omarchy/releases/tag/v4.5.0
- **Type:** Official software release and project-authored release notes
- **Use:** Establishes the release version and the project's reported scope: more than 740 merged pull requests, more than 180 contributors in twelve weeks, traditional desktop mode alongside tiling, Apple Silicon support and 50 interface languages.
- **Limitations:** Contributor and PR figures are project-reported release metrics; they do not establish active users, retention, revenue, reliability or long-term sustainability.
- **Editorial label:** VERIFIED (release metadata and wording); metrics remain project-reported.

### SRC-OMARCHY-QUATTRO-2026-001 — Omarchy v4.0.0 / Quattro
- **Project:** Omarchy / omacom
- **Release:** v4.0.0, published 2026-08-14
- **URL:** https://github.com/omacom/omarchy/releases/tag/v4.0.0
- **Type:** Official software release and project-authored release notes
- **Use:** Documents the move to a Quickshell-based desktop shell consolidating the bar, launcher, menus, notifications, OSD, control panels, lock screen and authentication agent.
- **Limitations:** Release notes establish the project's described architecture, not independent performance or reliability measurements.
- **Editorial label:** VERIFIED (release metadata and documented design); impact assessment is INTERPRETATION.

### SRC-QUICKSHELL-ABOUT-2026-001 — Quickshell official architecture overview
- **Project:** Quickshell
- **URL:** https://quickshell.org/about/
- **Type:** Official project documentation
- **Use:** Describes Quickshell as a desktop-shell toolkit based on QtQuick and QML, and lists integrations for windowing, compositor workspaces, PipeWire, BlueZ, authentication, power and media.
- **Limitations:** The list of integrations is not proof that every integration works identically across all compositors or distributions.
- **Editorial label:** VERIFIED (project description); compatibility must be tested per target.

### SRC-QT-QML-JS-2026-001 — Qt QML and JavaScript integration
- **Institution/project:** Qt Project
- **URL:** https://doc.qt.io/qt-6/qtqml-javascript-topic.html
- **Type:** Official language/runtime documentation
- **Use:** Documents that QML property bindings, signal handlers and methods can contain JavaScript expressions and that the QML engine provides a JavaScript host environment.
- **Limitations:** QML is not simply a browser application or ordinary JavaScript file; assess the actual QML/Qt runtime and code path rather than collapsing all Qt technology into web technology.
- **Editorial label:** VERIFIED (official language documentation). WARENA's policy disposition is a separate owner-directed decision.

### SRC-OMAXIAN-RELEASE-2026-001 — Omaxian v1.2.2
- **Project:** Omaxian / aozora
- **Release:** v1.2.2, published 2026-11-16
- **URL:** https://github.com/aozora/omaxian/releases/tag/v1.2.2
- **Repository:** https://github.com/aozora/omaxian
- **Type:** Official software release, repository metadata and README
- **Use:** Establishes the current release checked for the study and the project's stated purpose as an Omarchy-shell port for Debian-family systems using X11/XLibre and i3, without requiring Wayland, Hyprland or a specific init system.
- **Limitations:** A release and repository description do not prove compatibility with WARENA, Guix packaging, hardware support or independent validation of all listed features.
- **Editorial label:** VERIFIED (release metadata and repository description); WARENA suitability remains RESEARCH.

### SRC-GUIX-MANUAL-DESKTOP-2026-001 — GNU Guix configuration and generations
- **Project:** GNU Guix
- **URL:** https://guix.gnu.org/manual/en/
- **Configuration guide:** https://guix.gnu.org/manual/en/html_node/Using-the-Configuration-System.html
- **Type:** Official technical manual
- **Use:** Documents declarative system configuration, reconfiguration, system generations and rollback. The manual also documents `guix describe` for recording Guix/channel revisions.
- **Limitations:** These facilities do not automatically back up mutable user data, firmware, external services or every hardware-specific state. Documentation does not prove a WARENA host has been rebuilt or recovered.
- **Editorial label:** VERIFIED (documented Guix behaviour); WARENA host operation remains UNKNOWN until tested.

### SRC-RDE-UPSTREAM-2026-001 — RDE upstream repository
- **Project:** RDE / abcdw
- **URL:** https://github.com/abcdw/rde
- **Type:** Upstream source repository and project description
- **Use:** Identifies RDE as a Scheme-based framework for managing reproducible development environments and provides the upstream source of record.
- **Limitations:** Repository metadata is time-sensitive. A source repository or historical push date does not establish current maintenance activity, a pinned WARENA channel, Guix package availability or a successful local build.
- **Editorial label:** VERIFIED (repository identity and project description); current compatibility and maintenance status require a fresh review.
