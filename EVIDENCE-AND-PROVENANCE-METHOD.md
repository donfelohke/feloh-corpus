# FELOH Corpus — Evidence and Provenance Method

**Status:** Proposed research and archive method  
**Governing rule:** Preserve originals; make claims traceable; mark uncertainty.

## 1. Record types
Use explicit record types:
- SOURCE: original message, document, artefact or reference.
- FACT: claim directly supported by a cited source.
- INTERPRETATION: an author's reading of one or more sources.
- OPINION: a stated preference or judgement.
- HYPOTHESIS: a proposition requiring testing.
- PROPOSAL: a possible future action or design.
- DECISION: an explicit choice, with date and rationale when known.
- IMPLEMENTATION: a change actually made, linked to commit/PR or other evidence.
- TEST: method, environment, result and limitations.
- UNKNOWN: a material detail not yet verified.

Do not silently promote an opinion, recollection, proposal or generated summary into a sourced fact.

## 2. Minimum provenance record
For each item, capture stable record ID or source path; original title/author/source when known; source location and retrieval date where relevant; original timestamp if provided; preserved original or file where permitted; neutral description; record type and verification status; related claims, decisions, repositories and versions; rights, privacy, consent and publication restrictions; and corrections, supersession links and change history.

## 3. Preserve originals
Keep original source material immutable where practical. Put normalised extracts, annotations and summaries in separate files. If redaction is required, preserve a controlled original where lawful and appropriate, and record the reason and extent of redaction. Do not publish sensitive personal data or private correspondence merely because it is useful to the corpus.

## 4. Citation and claim rules
- Cite the smallest source segment that supports a claim.
- Distinguish direct quotation from paraphrase.
- Include contradictory evidence rather than smoothing it away.
- State source limitations; do not claim representativeness without support.
- Record external source title, publisher/author, publication date, URL and access date where available.
- If a detail cannot be verified, mark UNKNOWN and identify the next verification step.

## 5. Implementation evidence
A proposed change is not an implemented change. For software work, record repository, branch, pull request, commit, changed paths, test results and deployment verification separately. A merged pull request does not by itself prove a live deployment or successful user outcome.

## 6. Psychological and worldview material
When documenting opinions, worldview, creative process or self-reflection, preserve the author's own wording where possible, attribute interpretations clearly and avoid diagnosing or inferring sensitive traits. Separate the person's stated account from an editor's analysis. Restrict access to private or sensitive material according to consent and purpose.

## 7. Review checklist
- [ ] Original preserved or preservation limitation documented.
- [ ] Record type and status explicit.
- [ ] Claims trace to sources.
- [ ] Unknowns and contradictions retained.
- [ ] Privacy, rights and consent reviewed.
- [ ] Summary separated from source.
- [ ] Implementation claims link to verifiable evidence.
- [ ] Changes reviewed through a branch and pull request.
