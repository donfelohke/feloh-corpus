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
