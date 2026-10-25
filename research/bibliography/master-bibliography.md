# Source-by-source annotated master bibliography

**Working research document · Version 0.1 · 25 October 2026**  
**Status:** Initial reference set — **not** an exhaustive bibliography of Black life or of all primary materials  
**Standards:** [annotation-schema.md](./annotation-schema.md) · [evidence-labels.md](./evidence-labels.md)

External references below were **located** and their available descriptions **reviewed**. That is not the same as full-text examination of every work, nor authentication of every claim those works contain.

---

## A. Archival method, provenance and preservation

### MB-ARCH-001 — Library of Congress. “Archival Description.”

- **Source type:** Institutional archival guidance  
- **Status:** Located; description reviewed  
- **URL:** https://www.loc.gov/librarians/archival-description/  
- **Annotation:** Explains how archival collections are catalogued through inventories, registers, indexes and finding aids. Useful for provenance, scope, access conditions and descriptive standards when designing the FELOH Corpus inventory.  
- **Use:** Structure collection-level and item-level records; document origin and what remains inaccessible.  
- **Limitations:** Guidance on description does not establish authenticity or accuracy of a particular historical claim.

### MB-ARCH-002 — Oral History Association. *Archiving Oral History: Manual of Best Practices.*

- **Source type:** Professional practice manual  
- **Status:** Located; description reviewed  
- **URL:** https://oralhistory.org/archives-principles-and-best-practices-complete-manual/  
- **Annotation:** Accessioning, metadata, preservation, access, collaboration, ownership and rights; relationship between recordings, transcripts and related materials.  
- **Use:** Procedures for conversation exports, interviews, transcripts, consent records and contributor materials.  
- **Limitations:** Not a substitute for Kenyan legal advice, informed consent or community-specific cultural protocols.

### MB-ARCH-003 — Oral History Association. “Oral History Best Practices.”

- **Source type:** Professional standards  
- **Status:** Located; description reviewed  
- **URL:** https://oralhistory.org/best-practices/  
- **Annotation:** Preserving original recordings, redundant copies, documenting methods, contextualising excerpts with full-source references.  
- **Use:** Preservation copies, contextual citations, transcript links, restrictions.  
- **Limitations:** Recommendations are not evidence that a particular file is preserved or that consent was obtained.

---

## B. Black studies and African research discovery

### MB-BIB-001 — UCL Library Services. “Black Studies.”

- **Source type:** Research guide  
- **Status:** Located; description reviewed  
- **URL:** https://library-guides.ucl.ac.uk/black-studies  
- **Annotation:** Maps African Studies bibliographies, Black newspapers, oral histories, archival collections and related materials.  
- **Use:** Discover scholarship and primary-source collections.  
- **Limitations:** A discovery guide is not proof of a claim; some resources require subscription; assess records separately.

### MB-BIB-002 — African Journals Online (AJOL).

- **Source type:** Scholarly journal discovery platform  
- **Status:** Identified; individual articles **not** yet inventoried  
- **URL:** https://www.ajol.info/  
- **Annotation:** Route to scholarship in African academic journals; reduces exclusive reliance on non-African publishers.  
- **Use:** Search African intellectual traditions, history, culture, language, Kenyan society, etc.  
- **Limitations:** Inclusion on the platform does not establish an article’s conclusions; assess methods and venue per article.

### MB-BIB-003 — University of Cambridge Libraries. African Studies — Archives, Special Collections & Oral History.

- **Source type:** Archival discovery guide  
- **Status:** Located; description reviewed  
- **URL:** https://libguides.cam.ac.uk/africanstudies/archives-special-collections-oral-history  
- **Annotation:** African Studies archival resources, special collections, bibliographies, oral-history pathways.  
- **Use:** Locate historical records and catalogues, including holdings outside the communities documented.  
- **Limitations:** Note institutional context of collection assembly; archival survival is not a neutral complete past.

---

## C. Primary-source identification and interpretation

### MB-METH-001 — Amherst College Libraries. “Black Studies Research Guide: Find Primary Sources.”

- **Status:** Located; description reviewed  
- **URL:** https://libguides.amherst.edu/c.php?g=951607&p=6864354  
- **Annotation:** Digital primary-source collections relevant to Black Studies.  
- **Research value:** Locate first-hand materials connected to the research question.  
- **Limitation:** Primary vs secondary depends on the question; recollection is primary evidence of the speaker’s account, not automatic proof of every recalled detail.

### MB-METH-002 — UCL Library Services. “Black Studies: Databases.”

- **Status:** Located; description reviewed  
- **URL:** https://library-guides.ucl.ac.uk/black-studies/databases  
- **Annotation:** Distinguishes scholarly literature discovery from primary-source discovery.  
- **Research value:** Find documents and scholarship; register each item separately in this bibliography.  
- **Limitation:** Coverage and access vary; search results are not an exhaustive census.

---

## D. Internal source families (inventory targets)

These are **targets**, not a claim that every file is recovered or authenticated. Full rows belong in `../source-inventory/` as materials are accessioned.

| ID | Source family | Required annotation focus |
|----|---------------|---------------------------|
| MB-FEL-001 | Original ChatGPT conversations | Date, export, message boundaries, human vs assistant, attachments, retrieval status |
| MB-FEL-002 | Sun Burn — Black Musings originals | Title, text, creation date, versions, location, publication status |
| MB-FEL-003 | Manuscripts and notes | Filename, format, date, authorship evidence, drafts, checksum |
| MB-FEL-004 | Reflections / position statements | Voice, date, audience; reflection vs external assertion |
| MB-FEL-005 | Research notes / bibliographies | Search history, cites, unresolved claims, counterevidence |
| MB-FEL-006 | Photos, audio, video | Creator, date, place, rights, consent, restrictions |
| MB-FEL-007 | Published / public statements | Venue, edition, date, stable ID, completeness |
| MB-FEL-008 | AI-assisted derivatives | Input refs, tool, changes, human review status |
| MB-FEL-009 | Repository history / decisions | Commit/PR, date, rationale, verification evidence |

**Limitation (preserved):** Source inventory for *Sun Burn — Black Musings* remains incomplete; original creative work is not assumed imported or approved for publication merely because it is listed here.

---

## E. Coverage still required (subject shelves)

Create files under `subject-bibliographies/` as entries accumulate — do not pretendshelves are complete:

- African and Black intellectual histories  
- Kenyan and East African history  
- Living memory and cultural knowledge  
- Race, identity and social structures  
- Black literature and creative expression  
- Digital archives and data stewardship  
- Contemporary evidence (dated reports, datasets)

Organise by evidentiary role, not by preferred conclusion.

---

## Immediate priority

1. Inventory accessible conversations and *Sun Burn* originals into `source-inventory/`.  
2. Reconcile each item against existing corpus records.  
3. Only then expand external subject bibliographies and claim ledger rows.
