# Annotated Source Starter — Cross-Domain Research

**Status:** SOURCE DISCOVERY / INITIAL SCREENING.  
**Reviewed:** 2026-10-26 (landing pages and metadata checked where noted).  
**Important:** This is a reading queue, not a completed literature review. A registered source has not necessarily been read in full. Before relying on a substantive claim, inspect the relevant passage, record its version/page/section, and assess scope and limitations.

## How to use this file

- Start from the research question, not from a desire to accumulate links.
- Prefer primary documents for law, official statistics, technical specifications, and project behaviour.
- Treat curriculum pages and institutional overviews as orientation, not as proof that a particular method works.
- Separate source statements, direct observations, interpretation, and opinion.
- Record exact versions, access dates, and contradictions in the [source register](source-register.md).
- Never copy customer records, credentials, private messages, or sensitive personal data into public research records.

## Learning computer science and systems

### SRC-0011 — Teach Yourself Computer Science

- **URL:** https://teachyourselfcs.com/
- **Source type:** Curated educational roadmap / secondary orientation.
- **Best use:** Build a structured study plan across programming, algorithms, computer architecture, operating systems, networking, databases, languages/compilers, and distributed systems.
- **How to apply:** Choose one subject, identify its recommended textbook/course, work through exercises, then build a small reproducible project and document what was learned.
- **Limitations:** A curriculum is not a substitute for current platform documentation or practical verification. Check the page's current recommendations and each linked resource's edition/licence.
- **Screening status:** Landing page identified; full item-by-item review pending.

### SRC-0012 — GNU Guix Manual

- **URL:** https://guix.gnu.org/manual/
- **Source type:** Official technical documentation.
- **Best use:** Primary reference for Guix package management, channels, manifests, profiles, system configuration, services, and supported workflows.
- **How to apply:** Record the manual version alongside the Guix revision; test commands in a disposable or recoverable environment before adapting them to a real host.
- **Limitations:** Documentation version and installed Guix version can differ. A manual example does not establish that a particular configuration builds or behaves as intended.
- **Screening status:** Official landing page identified; relevant chapters and version still need to be recorded per implementation.

### SRC-0013 — Reproducible Builds: Definition

- **URL:** https://reproducible-builds.org/docs/definition/
- **Source type:** Technical project documentation / definition.
- **Best use:** Define reproducible build claims precisely: same specified source, environment, and instructions should yield bit-for-bit identical specified artefacts.
- **How to apply:** State which artefact is in scope, pin source and build inputs, build independently, and compare outputs.
- **Limitations:** A definition does not prove any project meets it. Non-deterministic inputs and artefact scope must be documented.
- **Screening status:** Landing-page definition checked; implementation-specific evidence required for any claim.

### SRC-0014 — GNU Free System Distribution Guidelines

- **URL:** https://www.gnu.org/distros/free-system-distribution-guidelines.html
- **Source type:** Primary project policy / software-freedom criteria.
- **Best use:** Clarify GNU's stated criteria for distributions recommended as respecting users' freedom.
- **Limitations:** This is a normative policy from the GNU Project, not a neutral comparative audit of every distribution. Attribute its criteria to GNU and corroborate factual claims about specific distributions separately.
- **Screening status:** Registered; detailed criterion-by-criterion review pending.

## Secure development and web accessibility

### SRC-0015 — NIST SP 800-218, Secure Software Development Framework (SSDF) v1.1

- **URL:** https://csrc.nist.gov/pubs/sp/800/218/final
- **Source type:** Government technical publication / recommended practices.
- **Best use:** Structure secure software-development practices and review questions across the lifecycle.
- **Limitations:** Recommendations require tailoring to project context; alignment is not certification or proof that a codebase is secure. Check for later revisions before formal adoption.
- **Screening status:** Official publication record checked; detailed control mapping pending.

### SRC-0016 — OWASP Application Security Verification Standard (ASVS)

- **URL:** https://asvs.owasp.org/
- **Source type:** Community-maintained security verification standard.
- **Best use:** Turn web-application security expectations into reviewable requirements and test cases.
- **Limitations:** Pin the ASVS release used. Requirements need threat-model context and evidence from actual tests; a checklist alone does not prove security.
- **Screening status:** Official project page checked; current published version shown as 5.0.0 at screening.

### SRC-0017 — W3C Web Content Accessibility Guidelines (WCAG) 2.2

- **URL:** https://www.w3.org/TR/WCAG22/
- **Source type:** W3C Recommendation / normative web standard.
- **Best use:** Derive accessibility review and test cases for public pages, forms, navigation, contrast, keyboard access, focus visibility, and touch interactions.
- **Limitations:** Conformance requires evaluating the relevant success criteria; a quick visual review or automated scan alone is insufficient. Select and document the intended conformance level.
- **Screening status:** W3C publication record checked; implementation testing still required.

## Kenya: data protection and economic context

### Existing source SRC-0001 — Kenya Data Protection Act, 2019 (dated consolidated source)

- **URL:** https://new.kenyalaw.org/akn/ke/act/2019/24/eng%402022-12-31/source
- **Source type:** Primary legal text.
- **Best use:** Investigate statutory duties and data-subject rights relevant to customer enquiries, contact information, service records, and research data.
- **Limitations:** The linked consolidated version is dated 2022-12-31. Check current amendments, related regulations, regulator guidance, and the specific legal context before drawing a compliance conclusion.
- **Screening status:** Registered; applicable provisions and currentness review pending.

### Existing source SRC-0002 — Office of the Data Protection Commissioner: Data Protection Laws in Kenya

- **URL:** https://www.odpc.go.ke/data-protection-laws-kenya/
- **Source type:** Official regulator legal-material index.
- **Best use:** Locate the Act, regulations, and official regulatory resources.
- **Limitations:** An index page is not a substitute for the underlying law or a legal opinion. Record each instrument separately when used.
- **Screening status:** Official landing page checked; individual instruments remain to be reviewed.

### SRC-0020 — Kenya National Bureau of Statistics, Economic Survey 2026

- **URL:** https://www.knbs.or.ke/reports/2026-economic-survey/
- **Source type:** Official national statistical publication.
- **Best use:** Establish dated macroeconomic and sectoral context for Kenya research, including employment, earnings, trade, ICT, and sector activity where the report supplies relevant data.
- **How to apply:** Cite the specific table, period, unit, and definition; compare like-for-like series and state whether a value is nominal or real where relevant.
- **Limitations:** National aggregates do not directly establish the size, income, or demand of a local target market in Eldoret or Lodwar. Use county-level or sector-specific evidence for local TAM/SAM/SOM.
- **Screening status:** KNBS landing page and report metadata checked; relevant tables not yet extracted.

## Movement and embodied creative practice

### Existing source SRC-0004 — Laban/Bartenieff Institute of Movement Studies: Research

- **URL:** https://labaninstitute.org/research/
- **Source type:** Institutional research/resource index.
- **Best use:** Locate relevant movement-studies publications, journals, archives, and research resources for GENJE and IKAI.
- **Limitations:** The institute overview is not evidence for every claim in an individual study. Follow links to the original publication and assess method, context, and scope.
- **Screening status:** Registered; identify and read specific studies before making substantive claims.

## Project repositories as first-party records

The following repositories can support claims about what the projects currently document, but not independent claims that a capability works:

- **SRC-0006 — FELOH Corpus:** https://github.com/donfelohke/feloh-corpus
- **SRC-0007 — WARENA:** https://github.com/donfelohke/WARENA
- **SRC-0008 — NAKEBUSEN:** https://github.com/donfelohke/NAKEBUSEN
- **SRC-0009 — IKAI:** https://github.com/donfelohke/Ikai
- **SRC-0010 — GENJE:** https://github.com/donfelohke/Genje

For each repository claim, cite a specific file, branch/commit, and test output when the claim concerns behaviour. A README or proposal is evidence of declared intent, not independent verification.

## Prioritised reading queue

1. **Public site quality:** WCAG 2.2 plus manual keyboard, focus, mobile, and real-device checks.
2. **Customer and research privacy:** current Kenya legal texts and ODPC guidance; map data flows before making compliance claims.
3. **Systems practice:** Guix manual plus a reproducibility test record tied to exact revisions and artefacts.
4. **Secure delivery:** NIST SSDF and a pinned ASVS release translated into project-specific checks.
5. **Market research:** KNBS tables for national context, then local evidence and transparent assumptions for the actual target market.
6. **Embodied practice:** specific Laban/Bartenieff research publications, retaining methods, context, disagreement, and limitations.
7. **Computer-science learning:** use Teach Yourself CS as a study map; record completed resources and practical exercises rather than marking the curriculum itself as completed.

## Status summary

**No complete literature review is claimed.** This file records a first source-discovery pass. For each research conclusion, add a separate claim record with the exact supporting passage/table/commit, counter-evidence, confidence rationale, and next verification step.
