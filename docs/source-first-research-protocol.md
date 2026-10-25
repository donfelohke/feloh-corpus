# Source-First Research Protocol

**Status:** PROPOSED  
**Scope:** FELOH Corpus and linked ecosystem repositories  
**Purpose:** Make research traceable, reproducible, reviewable, and safe to update.

This protocol is a proposed operating standard. Its presence in Git does not prove that every project follows it or that any automation is deployed.

## 1. Operating rule

**Source → Extract → Claim → Analysis → Recommendation → Decision → Implementation → Verification.**

Do not write a persuasive conclusion first and search only for supporting material. Seek disconfirming evidence and record important disagreement.

## 2. Source hierarchy

Rank sources by fitness for the particular claim, not by a universal prestige score.

1. **Primary evidence:** original documents, official records, source code, raw datasets, direct measurements, first-hand statements, signed decisions, reproducible test output.
2. **Authoritative secondary evidence:** official technical documentation, standards, peer-reviewed studies, regulator or institutional guidance.
3. **Independent reporting and analysis:** reputable journalism, independent audits, specialist research, practitioner investigations.
4. **Community and experiential sources:** issue threads, forums, reviews, social posts, interviews and field notes. Useful for lived experience and discovery; verify factual generalisations independently where possible.
5. **AI-generated material:** a lead, synthesis, translation or hypothesis only. Not independent evidence unless each factual assertion is traced to underlying sources.

A primary source is not automatically accurate or unbiased. Record scope, date, author/publisher, incentives, methodology and limitations when material.

## 3. Capture sources before summarising

For every material source, record:

- Stable source ID, such as `SRC-YYYY-NNN`.
- Exact title and author/organisation, if known.
- Canonical URL, repository path, DOI, archive reference or file identifier.
- Publication date and access/retrieval date (ISO 8601; include timezone where relevant).
- Source type and the exact claim(s) it supports or challenges.
- Relevant page, section, line range, commit SHA, dataset version, query, or timestamp.
- Short factual extract or faithful paraphrase; limit quotation and respect copyright.
- Method, population, geography, time period and known limitations.
- Rights/licence and privacy handling, where relevant.
- Integrity details where useful: commit SHA, checksum, release version or archived snapshot.
- Status: `CURRENT`, `NEEDS_RECHECK`, `SUPERSEDED`, `INACCESSIBLE`, or `DISPUTED`.

Do not silently replace a URL, file, dataset version or quote when the upstream source changes. Add a new source revision and record the difference.

## 4. Maintain a claim ledger

Assign stable IDs to claims that materially affect decisions, public copy, architecture, costs, safety, rights or implementation status (for example, `CLM-YYYY-NNN`).

For each claim record exact atomic wording; claim type; supporting and contradicting source IDs; confidence rationale; date validity, scope and assumptions; status; owner/reviewer if known; last verified date; next review trigger; and what would falsify the claim.

Claim types: `USER_CANON`, `OBSERVED`, `EXTERNAL_FACT`, `INTERPRETATION`, `ESTIMATE`, `RECOMMENDATION`, `UNKNOWN`.

Claim statuses: `SUPPORTED`, `PARTIALLY_SUPPORTED`, `CONTESTED`, `UNVERIFIED`, `SUPERSEDED`, `WITHDRAWN`.

A statement from the owner may establish owner-supplied brand canon, but does not by itself establish an independent linguistic, legal, scientific or market fact. Label it accordingly.

## 5. Research workflow

1. **Frame the question:** intended decision, audience, scope, exclusions, date horizon and acceptance criteria.
2. **Inspect existing canon:** search the FELOH Corpus and relevant specialist repositories before creating new definitions.
3. **Build a search plan:** list source types, query strings, date limits, geographic scope and blind spots.
4. **Capture evidence:** add source records before broad conclusions; preserve originals when permitted and necessary.
5. **Extract claims:** separate direct observations from interpretation; attach citations at claim level.
6. **Test alternatives:** search for counterevidence, contradictions, stale information, selection bias and missing populations.
7. **Analyse:** explain method, assumptions, uncertainty, limitations and what the evidence cannot establish.
8. **Recommend:** tie each recommendation to claims and sources; state trade-offs and confidence.
9. **Decide:** record accepted, rejected or deferred options and the accountable decision owner. Do not infer consensus.
10. **Implement separately:** use a focused branch and pull request. Research approval is not deployment approval.
11. **Verify:** record commands, tests, observations, environment, commit and result. Mark anything not checked `NOT VERIFIED`.
12. **Review over time:** re-check claims when sources change, a review date expires, the market/platform changes, or contradictory evidence appears.

## 6. Research deliverable structure

Every substantive report should contain: question and intended decision; scope/date/geography/exclusions; method and search log; sources and quality notes; findings with claim IDs and inline source references; contradictions and unknowns; analysis and limitations; recommendations ranked by impact, effort, risk and reversibility; decision record or explicit no-decision statement; implementation/verification status and next review triggers.

Use `docs/templates/research-record.md` as the starting point.

## 7. Git and review controls

- Never edit `main` directly for substantive research or canonical changes.
- Use a focused branch and PR; include scope, evidence, status changes, privacy/rights review and verification.
- Preserve source files and prior conclusions. Correct with a traceable amendment; do not erase contradictory history.
- Prefer Markdown, plain-text data, stable IDs, relative links and open formats.
- Pin software, datasets, queries and dependencies when reproducibility matters.
- Generated summaries must identify their source records and generation method. A generated view is not the canonical record.
- Automated checks may validate required fields and links, but cannot certify truth, consent, interpretation or research quality.
- Keep source records separate from customer operations, credentials, secrets, private correspondence and sensitive personal data. Never commit such material to public repositories.

## 8. AI use policy

AI may help discover sources, extract claims, compare versions, translate, draft summaries and propose tests. Verify material assertions against original sources; label synthetic or inferred content; do not treat multiple summaries of one source as independent corroboration; do not invent citations, quotations, market figures, customer feedback or test output. Require human review for canonical meaning, public claims, rights, sensitive content and consequential decisions. Do not permit unattended publication, payment, access changes, deletion or deployment solely on an AI recommendation.

## 9. Research maturity labels

- `CONCEPT`: idea or proposed method.
- `RESEARCH`: active investigation; conclusions may change.
- `PROTOTYPE`: artefact exists, with limited validation.
- `LIVE`: in actual use, supported by dated operational evidence.
- `HISTORICAL`: retained as a record of a past state.
- `SUPERSEDED`: replaced by a traceable later record.
- `UNKNOWN`: insufficient evidence to classify.

Use `NOT VERIFIED` for a specific check not performed. A green CI run verifies only the checks actually run, against the tested commit and environment.

## 10. Review and maintenance

Review this protocol at least annually, and earlier after a material privacy, rights, provenance or workflow failure. This interval is a recommendation, not an automated reminder unless one is configured and verified.

**Current maturity:** `PROPOSED` until accepted through repository review.  
**Implementation status:** This document alone does not create a database, scheduled review, source archive, automated checker or enforced policy.
