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
| SRC-SAGE-005 | Kazeem, Fayemi Ademola, “H. Odera Oruka and the Question of Methodology in African Philosophy: A Critique,” *Thought and Practice* 4(2), 2012, DOI 10.5840/tap20124211; https://www.ajol.info/index.php/tp/article/view/88147 | Methodological critique and scholarly reception | Secondary article; obtain full text for detailed claims |
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


## FELOH ecosystem alignment and cooperative infrastructure records — 2026-11-24

The following are first-party project records. They establish the projects' documented positions and research status; they are not independent evidence that a technical capability is deployed or that every underlying external claim has been verified.

| Source ID | Source | Type / supports | Limits / review status |
|---|---|---|---|
| SRC-FELOH-ECOSYSTEM-001 | [NAKEBUSEN × WARENA Brand Platform & Narrative Constitution](https://github.com/donfelohke/feloh-corpus/blob/main/docs/NAKEBUSEN-WARENA-BRAND-PLATFORM-2026-11-24.md) | Founder-approved governance record for shared identity, narrative, domain authority, evidence and maturity controls | First-party policy; not legal incorporation or external etymological proof. Read and indexed 2026-11-24. |
| SRC-FELOH-ECOSYSTEM-002 | [FELOH Corpus Ecosystem Alignment](https://github.com/donfelohke/feloh-corpus/blob/main/docs/ECOSYSTEM-ALIGNMENT-2026-11-24.md) | Repository roles, documentation boundaries, cross-project evidence rules and website exclusion | First-party alignment record; does not certify full repository audit or CI status. Read and indexed 2026-11-24. |
| SRC-WARENA-NET-001 | [WARENA Cooperative Networking, Federation and Self-Hosted Services](https://github.com/donfelohke/WARENA/blob/main/docs/research/cooperative-networking-and-self-hosted-services-2026-11-23.md) | Research map for community access networking, GNUnet, Tor, federation, self-hosting, databases, USSD and GNU Taler | Research only; source-page statements and compatibility claims require independent review before implementation. Read and indexed 2026-11-24. |
| SRC-GENJE-NET-001 | [GENJE Cooperative Networks and Embodied Media](https://github.com/donfelohke/Genje/blob/main/docs/research/GENJE-COOPERATIVE-NETWORKS-AND-EMBODIED-MEDIA-2026-11-23.md) | Creator-controlled exchange, embodied media, consent, rights and cooperative archive questions | Research only; no network or archive implementation claimed. Read and indexed 2026-11-24. |
| SRC-FELOH-NET-001 | [Cooperative Digital Infrastructure — Cross-Domain Research Update](https://github.com/donfelohke/feloh-corpus/blob/main/docs/research/COOPERATIVE-DIGITAL-INFRASTRUCTURE-CROSS-DOMAIN-UPDATE-2026-11-23.md) | Cross-domain routing and conceptual distinctions between networking, federation, privacy, self-hosting and governance | First-party synthesis; external technical claims must be checked against the linked primary sources before adoption. Read and indexed 2026-11-24. |
| SRC-IKAI-NAME-001 | [IKAI Ecosystem Alignment](https://github.com/donfelohke/Ikai/blob/main/docs/ECOSYSTEM-ALIGNMENT-2026-11-24.md) | Current attribution and uncertainty status of the proposed IKAI name association | First-party statement of uncertainty, not etymological evidence. Read and indexed 2026-11-24. |

Do not count these records as independent sources when they repeat one another. For external technical standards and project documentation cited inside the specialist dossiers, create separate source records only after checking the exact source page, version, publication date and relevant passage.


## Cross-repository standards and Kenya evidence intake — 2026-11-24

These records were checked against the linked institutional, standards-body or publication pages on 2026-11-24. “Checked” here means the source identity, metadata and cited summary/passage were inspected; it does not imply a full clause-by-clause standards audit, complete paper review or independent replication.

| Source ID | Source | Supports | Limits / use |
|---|---|---|---|
| SRC-ISO-25010-2023 | ISO/IEC 25010:2023, Product quality model, https://www.iso.org/standard/78176.html | Nine-characteristic ICT/software product-quality model for specification and evaluation | Standard abstract/page inspected; full text may require purchase. Use as an evaluation model, not certification evidence. |
| SRC-ISO-9241-210-2019 | ISO 9241-210:2019, Human-centred design for interactive systems, https://www.iso.org/standard/77520.html | Human-centred design principles and activities through interactive-system lifecycle | ISO page states confirmed current in 2025. Full normative text not reproduced here. |
| SRC-ISO-27001-2022 | ISO/IEC 27001:2022, Information security management systems, https://www.iso.org/standard/27001 | Requirements for an organisational information-security management system | Standard overview inspected; not a certification claim for any FELOH repository or business. |
| SRC-NIST-SSDF-001 | NIST SP 800-218, SSDF v1.1 (February 2022), https://csrc.nist.gov/pubs/sp/800/218/final | Secure software development practices across lifecycle | NIST publication abstract inspected; assess applicability and map actual controls. |
| SRC-SLSA-1.2-001 | SLSA v1.2 specification, https://slsa.dev/spec/v1.2/ | Source/build supply-chain security tracks and attestation formats | Approved specification pages inspected. A CI workflow alone does not establish a SLSA level. |
| SRC-SLSA-PROV-001 | SLSA Build Provenance v1.2, https://slsa.dev/spec/v1.2/build-provenance | Verifiable description of where, when and how build artefacts were produced | Specification page inspected; implementation and authenticity require actual attestations and verification. |
| SRC-SPDX-ISO-001 | ISO/IEC 5962:2021 / SPDX 2.2.1, https://www.iso.org/standard/81870.html | Standardised software package/component metadata exchange | ISO page inspected; SPDX metadata is not by itself a complete security or licence audit. |
| SRC-RB-DOCS-001 | Reproducible Builds documentation, https://reproducible-builds.org/docs/ | Deterministic build practices, build-environment recording and independent verification | Project documentation inspected; use pinned toolchain/source and independent rebuild logs for claims. |
| SRC-WCAG-22-001 | W3C WCAG 2.2, https://www.w3.org/TR/wcag/ | Testable web accessibility success criteria | W3C Recommendation; page inspected. Conformance requires criterion-by-criterion testing of the actual content and interaction states. |
| SRC-ISO-40500-2025 | W3C notice, “WCAG 2.2 Approved as an ISO Standard”, 2025-10-21, https://www.w3.org/WAI/news/2025-10-21/wcag22-iso/ | WCAG 2.2 approval as ISO/IEC 40500:2025 | Announcement inspected; consult ISO's publication for formal standard metadata and requirements. |
| SRC-OPENXR-REG-001 | Khronos OpenXR Registry, https://registry.khronos.org/OpenXR/ | OpenXR 1.1 API specifications, reference material, extensions and conformance test resources | Registry inspected; exact runtime, device, extension and driver support must be tested. |
| SRC-FAIR-2016-001 | Wilkinson et al., “The FAIR Guiding Principles for scientific data management and stewardship,” Scientific Data 3, 160018 (2016), https://doi.org/10.1038/sdata.2016.18 | Findable, Accessible, Interoperable and Reusable research data principles | Abstract/metadata inspected; FAIR does not confer consent or community authority. |
| SRC-CARE-2020-001 | Carroll et al., “The CARE Principles for Indigenous Data Governance,” Data Science Journal 19(1), 43 (2020), https://doi.org/10.5334/dsj-2020-043 | Collective Benefit, Authority to Control, Responsibility and Ethics; people- and purpose-oriented data governance | Peer-reviewed article metadata and abstract inspected; apply with relevant peoples/communities, not as a substitute for their authority. |
| SRC-UNESCO-ICH-2003-001 | UNESCO, Convention for the Safeguarding of the Intangible Cultural Heritage (2003), https://www.unesco.org/en/legal-affairs/convention-safeguarding-intangible-cultural-heritage | Convention scope and community-recognised intangible heritage | Official Convention text; legal applicability and national implementation require separate review. |
| SRC-UNESCO-ICH-ETHICS-2015-001 | UNESCO Ethical Principles for Safeguarding Intangible Cultural Heritage, https://ich.unesco.org/en/ethics-and-ich-00866 | Community primary role, transparent collaboration and free, prior, sustained and informed consent | Ethical principles are normative guidance within UNESCO's framework; adapt with local law and community authority. |
| SRC-CA-STAT-Q3-2025-26 | Communications Authority of Kenya, Third Quarter Sector Statistics Report FY2025/26 (1 Jan–31 Mar 2026), https://ca.go.ke/sites/default/files/2026-06/Sector%20Statistics%20Report%20Quarter%203%20%20FY%202025-2026.pdf | Active SIM subscriptions, mobile-data subscriptions, prepaid share, device counts and PAYG tariff tables | Operator-return statistics; CA states figures depend on provider returns. Active SIMs are not unique people. Cite exact table/page and reporting period. |
| SRC-CA-STAT-INDEX-001 | Communications Authority of Kenya, Statistics index, https://ca.go.ke/statistics | Quarterly sector-report update point | Index inspected; always select latest completed report and record its period, not the page crawl date. |
| SRC-KNBS-ECON-2026 | Kenya National Bureau of Statistics, Economic Survey 2026, https://www.knbs.or.ke/wp-content/uploads/2026/04/2026-Economic-Survey.pdf | 2025 employment estimates: 21.6 million recorded jobs, estimated 18.1 million informal-sector employment and 822,100 new jobs; 87.2% of new jobs in informal sector | National aggregate; excludes rural small-scale agriculture and pastoral activities. Informal-sector count is estimated; not a local beauty-market estimate. |
| SRC-UASIN-GISHU-CRR-2025 | Uasin Gishu County Review Report 2025, https://nepadaprmkenya.go.ke/wp-content/uploads/2025/07/UASIN-GISHU-County-Review-Report-FINAL-Annual-report-2025-V2-print.pdf | County-reported MSME finance and capacity-building programme outputs | County report; reported outputs are not independent causal or impact evaluation. Attribute figures to the county. |
| SRC-UASIN-GISHU-CIDP-2023-27 | County Government of Uasin Gishu, CIDP 2023–2027, repository record https://repository.kippra.or.ke/items/4441f0be-b136-4021-a21c-8603f5969f54 | County planning priorities, targets and programme context | Planning document, not proof targets were achieved. Check relevant programme tables and subsequent performance reports. |
| SRC-EPRA-ENERGY-2025-26 | EPRA, Biannual Energy & Petroleum Statistics Report FY2025/26, https://epra.go.ke/sites/default/files/2026-03/Biannual%20Statistics%20Report%202025-2026.pdf | Electricity generation/supply, reliability indices, pricing and renewable-energy statistics | Extract exact indices, tariff class and period before local system sizing; national generation mix is not local outage reliability. |
| SRC-KEN-ICT-POLICY-INDEX-001 | Ministry of ICT, Policy Documents index, https://ict.go.ke/policy-documents | Entry point to Kenya Cloud Policy, Kenya AI Strategy 2025–2030 and implementation roadmap, draft National Broadband Strategy 2025–2030 and related policy | Index includes drafts and published instruments. Record each document's status; do not cite a draft as enacted policy. |
| SRC-KEN-AI-STRATEGY-2025 | Republic of Kenya, Kenya Artificial Intelligence Strategy 2025–2030 (March 2025), https://www.ict.go.ke/sites/default/files/2025-06/National-AI-Strategy_IMPLEMENTATION.pdf | National AI policy context, local-language research, local context and data-governance priorities | Strategy, not an AI statute or proof of implementation. Read the specific section/table for each claim. |
| SRC-ODPC-KEN-LAW-001 | Office of the Data Protection Commissioner, Kenya data-protection laws index, https://www.odpc.go.ke/data-protection-laws-kenya/ | Data Protection Act 2019 and 2021 General, Registration, and Complaints Handling and Enforcement Regulations | Official entry point; read current legal text and applicable guidance before operational decisions. |
| SRC-NACOSTI-NSERS-001 | NACOSTI National Scientific and Ethics Review System, Guidelines & SOPs, https://nsers.nacosti.go.ke/guidelines-sops/ | Research licensing, ethics review, research quality and relevant STI Act / 2014 regulations | Official index; applicability depends on activity and researcher/institution status. Seek NACOSTI/ethics-body guidance where uncertain. |
| SRC-AAD-TRACTION-001 | American Academy of Dermatology, “Hairstyles that pull can lead to hair loss”, https://www.aad.org/public/diseases/hair-loss/causes/hairstyles | Public dermatology guidance on traction alopecia risk from tight styles, including locs | Professional public guidance, not a diagnosis or Kenya-specific clinical protocol. Do not turn it into a blanket claim that locs cause hair loss. |
| SRC-TRACTION-ALOPECIA-2008 | “Determinants of marginal traction alopecia in African girls and women,” PubMed record, https://pubmed.ncbi.nlm.nih.gov/18694677/ | Observational research on hairstyle-related symptoms and traction alopecia risk | Study population, design and limitations matter; do not generalise beyond the studied population or claim causation from association alone. |
| SRC-KEN-OSH-2007 | Kenya Ministry of Labour, Occupational Safety and Health Act 2007 entry, https://www.labour.go.ke/laws-regulations | Official access point for workplace safety legislation | Read the Act and relevant regulations; this record does not establish a salon-specific licence or complete premises checklist. |
| SRC-KEN-PH-1986-2020 | Kenya Public Health Act, Cap. 242 (revised 2020 copy), https://extranet.who.int/cpcd/sites/default/files/public_file_repository/KEN_Kenya_Public-Health-Act_1986asof2020.pdf | Public-health and sanitation statutory framework | Secondary-hosted copy of Kenyan legislation; verify current legal text through Kenya Law / official gazette before compliance advice. |

### Evidence-derived local design questions

- CA's Q3 FY2025/26 prepaid share and mobile-device mix justify testing low-data, interruptible and device-diverse experiences; they do not establish an individual customer's connectivity or affordability.
- KNBS and Uasin Gishu reports justify studying informal and micro-enterprise operating conditions; they do not establish demand, pricing power or revenue for NAKEBUSEN.
- EPRA data should be used to derive realistic power assumptions only after the relevant tariff and reliability tables are extracted for the intended location.
- Kenya's Data Protection Act, ODPC regulations and NACOSTI framework require an applicability assessment before identifiable participant, client, image, voice, movement or location data is collected.
- CARE and UNESCO principles add authority, benefit, consent and ethical obligations that a simple open-data or public GitHub licence cannot replace.



## Specialist source extraction — optical systems, movement notation and local operations — 2026-11-24

The following sources were inspected for a first specialist extraction pass. The linked project documents are research addenda and proposed validation protocols, not evidence that the proposed tests or compliance actions have been completed.

| Source ID | Source | Supports | Limits / use |
|---|---|---|---|
| SRC-GUIX-MANUAL-REPL-2026-001 | GNU Guix Reference Manual, [PDF](https://guix.gnu.org/manual/en/guix.pdf) | Channel pinning, `guix describe`, replication using saved channel commits and `guix time-machine` | Manual version must match the tested Guix revision; reproducible user-space packages do not reproduce firmware, mutable data or all hardware state. |
| SRC-OPENXR-REGISTRY-2026-001 | Khronos, [OpenXR Registry](https://registry.khronos.org/OpenXR/) | OpenXR 1.1 specifications, API references, extensions and conformance resources | Runtime/device/extension support must be checked on the actual target. Registry presence does not prove a WARENA or IKAI integration. |
| SRC-OPENXR-TIMING-2026-001 | Khronos, [OpenXR API reference — xrEndFrame](https://registry.khronos.org/OpenXR/specs/1.1/man/html/openxr.html) | Predicted display-time semantics and their relevance to motion judder/reprojection | XR frame timing is not a substitute for measuring physical camera-to-panel glass-to-glass latency. |
| SRC-ISO-3664-2025 | ISO, [ISO 3664:2025 — Viewing conditions](https://www.iso.org/standard/83759.html) | Controlled viewing conditions for reflective/transmissive image media | The 2025 edition supersedes 2009; its scope is not a mirror-display acceptance standard and it does not validate human appearance assessment. |
| SRC-ASTM-D1003-2021 | ASTM International, [ASTM D1003-21](https://store.astm.org/standards/d1003) | Haze and luminous transmittance measurement for transparent plastics | Plastic-specific scope; do not apply as a glass mirror test without a justified method and material match. Full standard may require purchase. |
| SRC-EN410-2026-001 | EN 410-1:2026, [standard catalogue record](https://standards.iteh.ai/catalog/standards/cen/a3922bba-1e6d-4625-a9c0-32d431c2160a/en-410-1-2026) | Glazing spectral transmittance/reflectance and luminous characteristics | Catalogue/preview source; confirm the current normative text and applicability to the selected mirror construction. |
| SRC-CIE-COLORIMETRY-001 | CIE, [Colorimetry, 4th Edition](https://cie.co.at/publications/colorimetry-4th-edition) | Colorimetric measurement framework | Use the correct edition, observer, illuminant, geometry and instrument; a colour-difference threshold alone is not an acceptance method. |
| SRC-LOC-DANCE-NOTATION-001 | Library of Congress, [Dance Notation Collection finding aid ](https://findingaids.loc.gov/) (legacy PDF path returned 404; exact collection record not yet re-identified) | Archival existence and distinct use of Benesh and Labanotation scores | Finding aid, not a complete technical manual for either notation system; access/reuse rights must be separately assessed. |
| SRC-HARVARD-DANCE-NOTATION-001 | Harvard Library, [Primary Sources for Performing Arts Research: Dance Notation](https://guides.library.harvard.edu/c.php?g=1294023&p=9509243) | Research pathways and distinction among movement-notation systems | Library research guide; use original manuals and specialist training for technical transcription. |
| SRC-OSU-DANCE-NOTATION-001 | Ohio State University Department of Dance, [Research and notation resources](https://dance.osu.edu/research/dnb/resources) | Labanotation, Motif and movement-analysis research resources | Institutional resource index; inspect original works for exact method and terminology. |
| SRC-WATTS-BENESH-LABAN-2015 | Victoria J. Watts, “Benesh Movement Notation and Labanotation: From Inception to Establishment (1919–1977),” *Dance Chronicle* 38(3), 2015, [DOI](https://doi.org/10.1080/01472526.2015.1085227) | Comparative history and distinct development of Benesh and Labanotation | Scholarly article; not a substitute for notation manuals or practitioner authority. |
| SRC-UG-REVENUE-PORTAL-001 | Uasin Gishu County, [County Revenue Management Self Service Portal](https://revenue.uasingishu.go.ke/) | County service categories and official revenue workflow entry point | Portal categories do not determine NAKEBUSEN's legal classification or confirm its permit status. |
| SRC-UG-SBP-EPROC-2024 | Government of Kenya eProcedures, [Uasin Gishu single business permit procedure](https://eprocedures.investkenya.go.ke/procedure/378/step/2038?embed=true&includeSearch=true&l=en) | Published application route, calendar-year validity and stated applicant information | Procedure page last modified 2024; verify current fee schedule and requirements with the County. Historic estimated fees are not current quotations. |
| SRC-ELDORET-BUSINESS-PERMIT-001 | City of Eldoret, [Apply for business permit](https://eldoretcity.go.ke/services/apply-for-business-permit-eldoret) | Current City service guidance to confirm activity category and fee through County workflow | Does not confirm a specific business's permit status, classification or fee. |
| SRC-KEN-COUNTY-LICENSING-ACT-2024 | Republic of Kenya, [County Licensing (Uniform Procedures) Act, 2024](https://new.kenyalaw.org/akn/ke/act/2024/8/eng%402024-12-28/publication) | Uniform procedural principles for county licensing | Read with current regulations and county legislation; does not set an individual business's category or prove a licence has been issued. |
| SRC-KEN-COUNTY-LICENSING-REGS-2025 | Republic of Kenya, [County Licensing (Uniform Procedures) Regulations, 2025, Legal Notice 91](https://new.kenyalaw.org/akn/ke/act/ln/2025/91/eng%402025-05-30/source) | Regulations associated with county licensing procedures | Verify current consolidated text and relevant procedural provisions before legal reliance. |
| SRC-KEN-PUBLIC-HEALTH-CAP242-2022 | Republic of Kenya, [Public Health Act, Cap. 242](https://new.kenyalaw.org/akn/ke/act/1921/38/eng%402022-12-31) | National public-health statutory framework | Use current Kenyan text and relevant county rules. Do not substitute an unrelated “Public Health Act 2009” source with salon-specific provisions. |
| SRC-AAD-TRACTION-001 | American Academy of Dermatology, [Hairstyles that pull can lead to hair loss](https://www.aad.org/public/diseases/hair-loss/causes/hairstyles) | Professional public guidance on traction risk | General professional guidance, not a diagnosis, Kenya-specific clinical protocol or proof that all locs cause hair loss. |
| SRC-TRACTION-ALOPECIA-2008 | “Determinants of marginal traction alopecia in African girls and women,” [PubMed record](https://pubmed.ncbi.nlm.nih.gov/18694677/) | Study-specific research on marginal traction alopecia | Study population/design must be reviewed; do not generalise beyond the evidence or infer diagnosis. |

### Specialist research outputs linked to this intake

- [WARENA — Reproducible Systems and Real-Time I/O Validation](https://github.com/donfelohke/WARENA/blob/main/docs/REPRODUCIBLE-SYSTEMS-AND-REALTIME-IO-VALIDATION-2026-11-24.md) — proposed Guix reproducibility, supply-chain and native media benchmark protocol.
- [IKAI — M1 Optical and Display Bench Addendum](https://github.com/donfelohke/Ikai/blob/main/docs/IKAI-M1-OPTICAL-AND-DISPLAY-BENCH-ADDENDUM-2026-11-24.md) — scope-aware optical standards and test matrix.
- [GENJE — Movement Notation and Interoperability Validation](https://github.com/donfelohke/Genje/blob/main/docs/GENJE-MOVEMENT-NOTATION-AND-INTEROPERABILITY-VALIDATION-2026-11-24.md) — notation provenance and round-trip validation.
- [NAKEBUSEN — Eldoret Loc-Care Operations and Regulatory Verification](https://github.com/donfelohke/NAKEBUSEN/blob/main/docs/ELDORET-LOC-CARE-OPERATIONS-AND-REGULATORY-VERIFICATION-2026-11-24.md) — county permit verification, hygiene controls and legal-status caveats.

These entries were checked for source identity, scope and the specific propositions summarised above on 2026-11-24. They do not imply complete reading of every full standard or law, independent field verification, completed testing or legal advice.
