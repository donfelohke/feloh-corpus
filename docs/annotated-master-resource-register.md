# Annotated Master Resource Register

**Register ID:** FELOH-MANIFEST-001 (working register; not a claim that a prior manifest has been recovered)  
**Prepared:** 2026-10-26  
**Status:** RESEARCH / STARTER REGISTER — links and descriptions are initial triage, not a completed source audit.  
**Canonical frame:** WARENA-CODEX-2026.09 v2.1 MASTER CANONICAL, subject to reconciliation against the actual canonical artifact and existing D01–D29 / M01–M16 taxonomy.

## Purpose

This register identifies source materials that can support the FELOH ecosystem's research, business practice, technical implementation, creative work, governance, and public documentation. It records why a resource matters and what must be verified before a claim or asset is reused.

A listing does not mean that the source has been read in full, that a claim is proven, that a licence permits reuse, or that a described system is implemented. Recheck availability, version, provenance, licence, and relevance at the point of use.

## Evidence and reuse labels

- **Source class:** PRIMARY / OFFICIAL / STANDARD / SCHOLARSHIP / DATASET / PRACTITIONER / OWNER-SUPPLIED / INTERNAL.
- **Review status:** DISCOVERED / TRIAGED / READ / CORROBORATED / IMPLEMENTED / SUPERSEDED / REJECTED.
- **Rights status:** VERIFY — inspect the resource-specific licence, terms, permissions, privacy, and attribution requirements. A link does not grant republication rights.
- **Evidence status:** SOURCE IDENTIFIED is not equivalent to CLAIM VERIFIED. Record claim-level support and contradictory evidence separately.
- **Domain mapping:** the domain codes below are provisional. Preserve the existing D01–D29 and M01–M16 taxonomy when its canonical mapping is recovered; do not silently remap or invent the missing taxonomy.

## Annotated resources

| ID | Domain / topic | Resource and direct link | Source class | Research value / annotation | Evidence and rights checks | Initial status |
|---|---|---|---|---|---|---|
| RSC-0001 | Kenya / macroeconomy | [Kenya National Bureau of Statistics](https://www.knbs.or.ke/) | OFFICIAL / DATASET | Starting point for Kenyan economic, labour, population, price and sector statistics. Use underlying tables and metadata for market sizing. | Record publication/table, reference year, definitions, geography, sampling and revisions; verify reuse terms. | DISCOVERED |
| RSC-0002 | Kenya / enterprise policy | [Micro and Small Enterprises Authority](https://msea.go.ke/) | OFFICIAL | Policy, enterprise development and support context for micro and small businesses. | Confirm current programmes and eligibility directly; distinguish policy intent from measured outcomes. | DISCOVERED |
| RSC-0003 | Kenya / business registration | [Business Registration Service](https://brs.go.ke/) | OFFICIAL | Official starting point for business registration and registry procedures. | Verify current process, fees and legal requirements from current official notices. | DISCOVERED |
| RSC-0004 | Kenya / intellectual property | [Kenya Industrial Property Institute](https://www.kipi.go.ke/) | OFFICIAL | Starting point for trademark and industrial-property research relevant to NAKEBUSEN, WARENA, IKAI and related marks. | A preliminary search is not legal clearance; document exact mark, class, territory, date and result. | DISCOVERED |
| RSC-0005 | Kenya / data protection | [Office of the Data Protection Commissioner](https://www.odpc.go.ke/) | OFFICIAL | Guidance and legal materials for personal-data handling, customer records, photography consent and privacy-aware operations. | Verify current law and guidance; avoid storing customer records in public Git. | DISCOVERED |
| RSC-0006 | Beauty / loc services | [NAKEBUSEN repository](https://github.com/donfelohke/NAKEBUSEN) | INTERNAL / OWNER-SUPPLIED | Source of approved public business copy, service catalogue and operating boundaries. Owner-supplied meaning should be attributed unless independently documented. | Recheck current approved services, prices, locations and contact channels before publishing; never infer bookings or outcomes. | TRIAGED |
| RSC-0007 | Brand / canon | [FELOH Sovereign Corpus](https://github.com/donfelohke/feloh-corpus) | INTERNAL / CANONICAL-INTENDED | Shared terminology, governance, decision provenance, brand relationships and implementation-status discipline. | Verify individual document status and canonical lineage; do not treat concepts as implementation evidence. | TRIAGED |
| RSC-0008 | Computing / reproducibility | [GNU Guix Manual](https://guix.gnu.org/manual/) | OFFICIAL / TECHNICAL | Reference for declarative package management, system configuration, environments and reproducible software workflows relevant to WARENA. | Record version and tested commands; distinguish upstream capability from WARENA implementation. Check component licences. | DISCOVERED |
| RSC-0009 | Computing / operating systems | [Linux Kernel Documentation](https://docs.kernel.org/) | OFFICIAL / TECHNICAL | Primary technical documentation for kernel interfaces, subsystems, drivers and development. | Cite the relevant page and kernel version; verify target hardware compatibility. | DISCOVERED |
| RSC-0010 | Computing / security | [OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/) | TECHNICAL / PRACTITIONER | Practical security guidance for authentication, secrets, access control and deployment. | Apply threat modelling; a checklist alone does not demonstrate security. Check licence and version. | DISCOVERED |
| RSC-0011 | Computing / security framework | [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework) | OFFICIAL / FRAMEWORK | Organises cybersecurity outcomes and risk-management discussion for small-business and infrastructure services. | Map recommendations to actual controls; do not claim compliance without assessment. | DISCOVERED |
| RSC-0012 | Networking / standards | [IETF RFC Editor](https://www.rfc-editor.org/) | STANDARDS | Protocol specifications for networking, Internet architecture and interoperability. | Cite exact RFC and status; test actual configuration independently. | DISCOVERED |
| RSC-0013 | Web / accessibility | [W3C WCAG 2.2](https://www.w3.org/TR/WCAG22/) | STANDARD | Criteria for accessible content and interaction, including keyboard use, contrast, focus and forms. | Record conformance target and test results; do not claim conformance from visual inspection alone. | DISCOVERED |
| RSC-0014 | Web / HTML | [WHATWG HTML Living Standard](https://html.spec.whatwg.org/) | STANDARD | Normative reference for HTML behaviour relevant to portable, offline-friendly pages. | Verify browser support and test target devices. | DISCOVERED |
| RSC-0015 | Web / CSS / browser compatibility | [MDN Web Docs](https://developer.mozilla.org/) | TECHNICAL / SECONDARY | Accessible explanations and compatibility references for HTML, CSS, JavaScript and browser APIs. | Prefer normative sources for disputed behaviour; record browser/version test evidence. Review MDN content licence before reuse. | DISCOVERED |
| RSC-0016 | Publishing / source control | [Git documentation](https://git-scm.com/doc) | OFFICIAL / TECHNICAL | Reference for version control, diffs, branches, tags and change history. | A commit records a change but does not prove runtime behaviour or truth of content. | DISCOVERED |
| RSC-0017 | Publishing / hosting | [GitHub Pages documentation](https://docs.github.com/en/pages) | OFFICIAL / TECHNICAL | Hosting, build and deployment reference for public sites and documentation. | Check repository settings, workflow logs, deployed URL and observed behaviour. | DISCOVERED |
| RSC-0018 | Licensing / creative works | [Creative Commons licence chooser](https://creativecommons.org/chooser/) | OFFICIAL / LICENSING | Helps select a Creative Commons licence for eligible documentation and creative works. | Confirm ownership and third-party rights first; CC is not appropriate for every software or asset case. | DISCOVERED |
| RSC-0019 | Sound / livecoding | [SuperCollider documentation](https://doc.sccode.org/) | OFFICIAL / TECHNICAL | Reference for synthesis, algorithmic composition, sound processes and live electronic performance. | Record version, platform and tested patch; check licences for code, samples and assets. | DISCOVERED |
| RSC-0020 | Creative technology / livecoding | [TOPLAP](https://toplap.org/) | COMMUNITY / PRACTITIONER | Community context and resources for livecoding and performance practices. Useful for locating examples, not a substitute for peer-reviewed evidence. | Attribute individual works and authors; verify each project's licence and permission. | DISCOVERED |
| RSC-0021 | Creative coding / music | [Tidal Cycles documentation](https://tidalcycles.org/) | PROJECT / TECHNICAL | Documentation for pattern-based livecoding and algorithmic music workflows. | Verify software version and dependencies; review repository-specific licences. | DISCOVERED |
| RSC-0022 | Movement / somatic practice | [Laban/Bartenieff Institute of Movement Studies](https://www.limsonline.org/) | INSTITUTIONAL / PRACTITIONER | Starting point for Laban Movement Analysis and Bartenieff Fundamentals training and institutional resources. | Distinguish institutional descriptions, scholarship, practitioner interpretation and original synthesis; check teaching-material permissions. | DISCOVERED |
| RSC-0023 | Research / scholarly discovery | [Crossref Search](https://search.crossref.org/) | METADATA / DISCOVERY | Discover and validate DOI metadata for scholarly publications. | Metadata is not peer review or evidence quality; verify publisher record, full text and corrections. | DISCOVERED |
| RSC-0024 | Research / open scholarly literature | [Directory of Open Access Journals](https://doaj.org/) | INDEX / DISCOVERY | Discover open-access journals and articles for relevant research topics. | Journal inclusion is a discovery signal, not automatic validation of every article; assess methods. | DISCOVERED |
| RSC-0025 | African philosophy / intellectual history | [Internet Encyclopedia of Philosophy](https://iep.utm.edu/) | REFERENCE / SECONDARY | Introductory reference for locating concepts, thinkers and bibliographies in philosophy, including African philosophy where covered. | Trace important claims to original works and specialist scholarship; record author and revision date. | DISCOVERED |
| RSC-0026 | Historical research / archives | [Digital Public Library of America](https://dp.la/) | DISCOVERY / AGGREGATION | Discovery route for digitised cultural and historical collections; useful for finding original holding institutions. | Verify originating institution, metadata, context, access restrictions and reuse rights for each item. | DISCOVERED |
| RSC-0027 | Heritage / language / culture | [Endangered Languages Project](https://www.endangeredlanguages.com/) | DISCOVERY / COMMUNITY | Discovery route for language documentation. Use as a lead for locating Turkana and Ateker materials, not as a claim that a particular resource is present or authoritative. | Verify language/dialect, author/community authority, date, consent, restrictions and transcription conventions with source holders. | DISCOVERED |
| RSC-0028 | Hardware / embedded systems | [Raspberry Pi Documentation](https://www.raspberrypi.com/documentation/) | OFFICIAL / TECHNICAL | Hardware and software documentation useful for embedded-computing comparisons and prototyping methods. | Not proof of compatibility with other boards; identify exact model and test target hardware. | DISCOVERED |
| RSC-0029 | Research methods / evidence | [EQUATOR Network](https://www.equator-network.org/) | RESOURCE HUB / METHODS | Reporting guidelines for health and related research; relevant only where a project enters those research domains. | Select guidelines appropriate to the study type; do not apply clinical checklists indiscriminately to business or cultural research. | DISCOVERED |
| RSC-0030 | Internal / prior corpus artifacts | [FELOH Corpus repository](https://github.com/donfelohke/feloh-corpus) — reconcile WARENA-CODEX-2026.09 v2.1 MASTER CANONICAL, FELOH-1DOC-CANONICAL-MASTER-REV008.md/.docx, FELOH Sovereign System Master Corpus_2026-10-14.html and prior manifest references | INTERNAL / HISTORICAL | Prior context identifies candidate artifacts and a claimed earlier extraction of 29 deduplicated external URLs. Locate and compare the files before treating that extraction as reproducible. | Filename and prior mention do not prove file presence or canonical status. Verify exact blobs, versions, checksums, lineage, D01–D29 and M01–M16 mappings. | UNRESOLVED |

## Research gaps and next actions

1. **Recover the existing taxonomy.** Locate authoritative D01–D29 domain definitions and M01–M16 material classes; reconcile rather than replace them.
2. **Reconcile prior manifests.** Find and inspect the earlier FELOH-MANIFEST-001-RESOURCE-REGISTER.csv, source ZIP and master update if present. Compare every row with current source artifacts.
3. **Promote sources only after review.** Capture exact title, creator, publication/version date, direct URL or DOI, access date, summary, method, limitations, supported claim IDs, rights and reviewer.
4. **Add claim-level evidence.** Create stable claim IDs and link each material factual claim to the specific source passage, table, test, observation or attributed testimony.
5. **Add Kenya- and county-specific research.** Prioritise verified Eldoret/Uasin Gishu and Lodwar/Turkana service demand, competitor observations, business costs, beauty-sector practice, digital-service demand and official economic data. Do not fabricate TAM figures or competitor facts.
6. **Add source-holder-led heritage research.** Identify authoritative Turkana/Ateker language resources, community archives, oral-history protocols and relevant African/Black scholarship. Respect attribution, consent and access restrictions.
7. **Audit implementation claims separately.** Link technical documentation to reproducible tests, supported device/software versions, observed results and limitations.
8. **Verify rights before publication.** A public URL is not permission to copy a full text, image, dataset, recording, code sample or cultural work.
9. **Preserve and review.** Keep the register in version control, add review dates and supersession links, and maintain an offline copy with integrity checks.

## Acceptance checklist

- [ ] D01–D29 and M01–M16 mappings recovered and reconciled.
- [ ] Prior manifest and source artifacts found or explicitly marked unavailable.
- [ ] Each resource has exact metadata, direct link, source class, domain mapping and review status.
- [ ] Important claims have claim-level citations and contradictions recorded.
- [ ] Licence, consent, privacy and cultural restrictions reviewed before reuse.
- [ ] Implementation claims linked to actual test or observation evidence.
- [ ] Links and repository paths checked.
- [ ] Offline preservation and integrity procedure documented.

**Current acceptance:** This is a curated starter register of discovery resources. It is not yet the complete annotated master bibliography, the recovered 29-URL inventory, or proof that all cited materials have been read, licensed for reuse, or verified.