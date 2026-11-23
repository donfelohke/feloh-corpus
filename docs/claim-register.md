# Initial Claim Register — Source-Page Facts

**Status:** INITIAL EXTRACTION / BOUNDED CLAIMS.  
**Reviewed:** 2026-10-26.  
**Scope:** These records capture a small number of claims visible on official project/standards/statistics landing pages. They do not constitute full-document review or a comprehensive literature review. Re-check the source before using a claim in a public-facing decision.

## CLM-0001 — Definition of a reproducible build

- **Claim:** The Reproducible Builds project defines a reproducible build in terms of the same source code, build environment, and instructions allowing another party to recreate bit-for-bit identical copies of the specified artefacts.
- **Source:** [Reproducible Builds — Definition](https://reproducible-builds.org/docs/definition/)
- **Source type:** Project technical documentation.
- **Editorial status:** VERIFIED AT SOURCE-PAGE LEVEL.
- **Scope/limits:** This records the definition, not evidence that any WARENA build is reproducible. A project claim still needs a named artefact, pinned inputs, and independent output comparison.
- **Next check:** Apply the definition to one explicitly scoped build and record source revision, environment, instructions, artefact hash, and independent rebuild result.

## CLM-0002 — WCAG 2.2 publication status

- **Claim:** W3C identifies WCAG 2.2 as a W3C Recommendation dated 12 December 2024.
- **Source:** [W3C — WCAG 2.2](https://www.w3.org/TR/WCAG22/)
- **Source type:** Standards publication.
- **Editorial status:** VERIFIED AT SOURCE-PAGE LEVEL.
- **Scope/limits:** Publication status does not establish that the NAKEBUSEN website or any other page conforms to WCAG. Conformance requires criterion-level evaluation of the relevant content and interactions.
- **Next check:** Choose a target conformance level and document keyboard, focus, contrast, responsive, and assistive-technology testing for the deployed site.

## CLM-0003 — NIST SSDF publication metadata

- **Claim:** NIST SP 800-218, Secure Software Development Framework (SSDF) Version 1.1, is a recommendation framework for mitigating software vulnerability risk; the NIST publication page lists its publication date as February 2022.
- **Source:** [NIST SP 800-218 final publication](https://csrc.nist.gov/pubs/sp/800/218/final)
- **Source type:** Government technical publication.
- **Editorial status:** VERIFIED AT SOURCE-PAGE LEVEL.
- **Scope/limits:** This does not prove that any repository follows SSDF or is secure. The framework must be mapped to project scope, and current revisions should be checked before formal adoption.
- **Next check:** Select applicable practices and link each to a real workflow, repository control, test, or documented gap.

## CLM-0004 — OWASP ASVS release metadata

- **Claim:** The OWASP ASVS project page lists version 5.0.0 as a stable release published on 30 May 2025.
- **Source:** [OWASP Application Security Verification Standard](https://asvs.owasp.org/)
- **Source type:** Community-maintained security verification standard.
- **Editorial status:** VERIFIED AT SOURCE-PAGE LEVEL.
- **Scope/limits:** Version metadata is not an assessment of any application. Requirements must be selected and tested in the relevant threat model.
- **Next check:** Pin the version and map relevant requirements to the public site or any future application before claiming a security review.

## CLM-0005 — Kenya Economic Survey 2026: headline real GDP growth

- **Claim:** The KNBS 2026 Economic Survey landing page reports that Kenya's real GDP grew by 4.6% in 2025, compared with 4.7% in 2024.
- **Source:** [KNBS — 2026 Economic Survey](https://www.knbs.or.ke/reports/2026-economic-survey/)
- **Source type:** Official national statistical publication landing page.
- **Editorial status:** VERIFIED AT SOURCE-PAGE LEVEL; TABLE-LEVEL REVIEW PENDING.
- **Scope/limits:** This is a national headline statistic, not a measure of the local beauty-services or small digital-services market in Eldoret or Lodwar. It must not be used as a proxy for local demand or TAM.
- **Next check:** Inspect the relevant report/table for definitions and revisions; seek local, sector-specific data and label any market-size assumptions separately.

## CLM-0006 — Kenya data-protection law exists as a statutory framework

- **Claim:** The Office of the Data Protection Commissioner lists the Data Protection Act, 2019, and related regulations among Kenya's data-protection legal instruments.
- **Source:** [ODPC — Data Protection Laws in Kenya](https://www.odpc.go.ke/data-protection-laws-kenya/)
- **Source type:** Official regulator index.
- **Editorial status:** VERIFIED AT SOURCE-PAGE LEVEL.
- **Scope/limits:** The index is not a complete legal analysis. It does not by itself determine which duties apply to a specific operation, nor does it establish compliance.
- **Next check:** Review current legal texts and relevant regulations before making a compliance decision; document the actual data flow and purpose.

## CLM-0007 — IKAI's current documented agenda is a set of research questions

- **Claim:** The current IKAI research agenda labels its questions as candidate questions rather than completed research findings.
- **Source:** [IKAI research agenda](https://github.com/donfelohke/Ikai/blob/main/docs/research-agenda.md)
- **Source type:** First-party project documentation.
- **Editorial status:** VERIFIED AS A STATEMENT IN THE REFERENCED PROJECT DOCUMENT.
- **Scope/limits:** A repository's own statement is evidence of declared project status, not independent validation of its privacy or technical properties.
- **Next check:** Link any future claim about a prototype or experiment to a specific commit, protocol, observed test, and limitation record.

## CLM-0008 — Project documentation is not independent implementation evidence

- **Claim:** A README or proposed runbook establishes what a project documents or intends, but cannot alone establish that a capability has been deployed, tested, or independently reproduced.
- **Sources:** [WARENA architecture](https://github.com/donfelohke/WARENA/blob/main/docs/architecture.md); [Reproducible Builds definition](https://reproducible-builds.org/docs/definition/)
- **Source type:** Methodological rule derived from the corpus's evidence policy and reproducible-build definition.
- **Editorial status:** INTERPRETATION / GOVERNANCE RULE.
- **Rationale:** The first source describes an evidence discipline; the second defines a specific reproducibility test. The conclusion is a rule for how the corpus should evaluate claims, not a quotation from either source.
- **Scope/limits:** Different claims require different evidence. A file existence check, build, deployment, and recovery test establish different things.
- **Next check:** Apply a claim-specific evidence checklist in each specialist repository.

## Editorial rules for this register

- “Verified at source-page level” means the stated metadata or wording was visible on the cited page during this screening pass; it does not mean the full underlying document was read.
- Use the exact source version and date when a source is versioned or legally consequential.
- Keep source claims separate from local observations and recommendations.
- If a source changes, re-check the record and update the review date.
- Do not convert a source-page fact into an unsupported local-market, product-performance, legal-compliance, or implementation claim.


## CLM-0009 — Omarchy v4.5.0 release and project-reported activity
- **Claim:** Omarchy v4.5.0 was published on 2026-11-05. Its release notes report more than 740 merged pull requests from more than 180 contributors in twelve weeks, a traditional desktop mode alongside tiling, Apple Silicon support and 50 interface languages.
- **Source:** [Omarchy v4.5.0 release](https://github.com/omacom/omarchy/releases/tag/v4.5.0)
- **Source type:** Official software release and project-authored notes.
- **Editorial status:** VERIFIED (release metadata and release-note wording); PROJECT-REPORTED (activity metrics).
- **Scope/limits:** These metrics do not establish active users, retention, reliability, financial sustainability or a stable contributor base.
- **Next check:** Review subsequent releases and contributor/maintenance patterns over time; do not treat download or star counts as retained users.

## CLM-0010 — Omarchy Quattro consolidated desktop-shell functions
- **Claim:** Omarchy v4.0.0 describes a Quickshell-based shell consolidating multiple desktop-shell functions that were previously separate components.
- **Source:** [Omarchy v4.0.0 release](https://github.com/omacom/omarchy/releases/tag/v4.0.0)
- **Source type:** Official software release and project-authored architecture description.
- **Editorial status:** VERIFIED AS PROJECT-DOCUMENTED ARCHITECTURE.
- **Scope/limits:** The release description is not an independent benchmark of performance, fault isolation, security or maintainability.
- **Next check:** Inspect source and issue history before drawing implementation-level conclusions.

## CLM-0011 — Omaxian is an X11/XLibre and i3 port of the Omarchy shell
- **Claim:** Omaxian's official repository describes a Debian-family port using X11/XLibre and i3; the latest release endpoint checked returned v1.2.2, published 2026-11-16.
- **Source:** [Omaxian repository](https://github.com/aozora/omaxian); [v1.2.2 release](https://github.com/aozora/omaxian/releases/tag/v1.2.2)
- **Source type:** Official source repository and release metadata.
- **Editorial status:** VERIFIED (repository description and release metadata).
- **Scope/limits:** This establishes the project's declared scope and release, not WARENA compatibility, Guix packaging, hardware validation or equivalence with the original Omarchy implementation.
- **Next check:** Inspect the pinned source and file-level port notes for any implementation comparison.

## CLM-0012 — QML supports JavaScript expressions and methods
- **Claim:** Qt's QML documentation states that property bindings, signal handlers and methods can contain JavaScript expressions, with a JavaScript host environment provided by the QML engine.
- **Source:** [Qt — Integrating QML and JavaScript](https://doc.qt.io/qt-6/qtqml-javascript-topic.html)
- **Source type:** Official language/runtime documentation.
- **Editorial status:** VERIFIED AT DOCUMENTATION LEVEL.
- **Scope/limits:** QML is not equivalent to a browser-hosted web application. The claim is limited to QML's documented JavaScript integration and is used to assess WARENA's existing policy, not to make a general judgement about Qt.
- **Next check:** Evaluate the actual QML and runtime dependency graph of any candidate before proposing a policy exception.

## CLM-0013 — Guix documents system generations and rollback
- **Claim:** GNU Guix documents that system reconfiguration creates generations and that previous generations can be selected or restored; `guix describe` records Guix/channel revision information.
- **Source:** [GNU Guix manual](https://guix.gnu.org/manual/en/); [Using the Configuration System](https://guix.gnu.org/manual/en/html_node/Using-the-Configuration-System.html)
- **Source type:** Official technical manual.
- **Editorial status:** VERIFIED AT DOCUMENTATION LEVEL.
- **Scope/limits:** This does not prove that a WARENA host has been configured, rebuilt, booted or recovered. System generations do not replace backup of mutable user data or external state.
- **Next check:** Run a controlled VM reconfigure, inspect channel provenance, boot a prior generation and separately test user-data restoration before making a WARENA operational claim.


## CLM-0013 — Cooperative digital infrastructure research is not a deployment record

- **Claim:** The current cross-domain cooperative infrastructure dossier explicitly classifies the work as research and states that no network build, radio survey, benchmark, deployment, provider integration or legal review is claimed.
- **Sources:** [WARENA cooperative networking research](https://github.com/donfelohke/WARENA/blob/main/docs/research/cooperative-networking-and-self-hosted-services-2026-11-23.md); [FELOH Corpus cross-domain synthesis](https://github.com/donfelohke/feloh-corpus/blob/main/docs/research/COOPERATIVE-DIGITAL-INFRASTRUCTURE-CROSS-DOMAIN-UPDATE-2026-11-23.md).
- **Source type:** First-party project research records.
- **Editorial status:** VERIFIED AS A STATEMENT IN THE REFERENCED PROJECT DOCUMENTS.
- **Scope/limits:** This verifies what the documents declare, not the absence of unrecorded activity outside the repositories or the technical correctness of every cited external source.
- **Next check:** Record any later site survey, hardware selection, test protocol, observed result, provider agreement or legal review as a separate dated evidence record.

## CLM-0014 — Shared brand platform assigns specialist domain authority

- **Claim:** The canonical FELOH brand platform assigns customer-facing service facts to NAKEBUSEN, technical implementation evidence to WARENA, creative-work provenance to GENJE, reflective-computing and participant safeguards to IKAI, asset-level rights to Gallery, and shared terminology/evidence to FELOH Corpus.
- **Source:** [NAKEBUSEN × WARENA Brand Platform & Narrative Constitution](https://github.com/donfelohke/feloh-corpus/blob/main/docs/NAKEBUSEN-WARENA-BRAND-PLATFORM-2026-11-24.md).
- **Source type:** Founder-approved first-party governance document.
- **Editorial status:** VERIFIED AS AN ADOPTED GOVERNANCE STATEMENT; NOT AN EXTERNAL FACT CLAIM.
- **Scope/limits:** This records the internal authority model. It does not establish legal incorporation, contractual rights or operational compliance.
- **Next check:** Reconcile specialist READMEs and operational records against the stated authority model during future audits.

## CLM-0015 — IKAI name attribution remains unverified

- **Claim:** IKAI's current public repository note labels the proposed Turkana female-name association with “home” as unverified pending language-variety, spelling, pronunciation, morphology and community consultation.
- **Source:** [IKAI ecosystem alignment record](https://github.com/donfelohke/Ikai/blob/main/docs/ECOSYSTEM-ALIGNMENT-2026-11-24.md).
- **Source type:** First-party project documentation.
- **Editorial status:** VERIFIED AS A STATEMENT IN THE REFERENCED PROJECT DOCUMENT.
- **Scope/limits:** This records the project's stated uncertainty; it does not verify the proposed etymology.
- **Next check:** Obtain competent Turkana linguistic review and attributed community testimony before presenting the meaning as established.
