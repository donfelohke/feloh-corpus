# Claim Ledger Template

**Purpose:** Maintain atomic, source-linked claims without confusing owner-supplied canon, observation, external fact, analysis and recommendation.

Copy this file into a research-specific ledger or adapt it for machine-readable TSV/CSV when appropriate. Keep one claim per row.

| Claim ID | Exact claim | Type | Scope / validity | Supporting source IDs | Contradicting source IDs | Status | Confidence rationale | Last verified | Review trigger | Falsifier / missing evidence |
|---|---|---|---|---|---|---|---|---|---|---|
| CLM-YYYY-NNN | | UNKNOWN | | | | UNVERIFIED | | | | |

## Controlled vocabularies

**Type:** `USER_CANON`, `OBSERVED`, `EXTERNAL_FACT`, `INTERPRETATION`, `ESTIMATE`, `RECOMMENDATION`, `UNKNOWN`.

**Status:** `SUPPORTED`, `PARTIALLY_SUPPORTED`, `CONTESTED`, `UNVERIFIED`, `SUPERSEDED`, `WITHDRAWN`.

**Source status:** `CURRENT`, `NEEDS_RECHECK`, `SUPERSEDED`, `INACCESSIBLE`, `DISPUTED`.

## Rules

1. Write claims so another person can tell what evidence would confirm or disprove them.
2. Cite source IDs, not just a homepage or search-results page.
3. Keep supporting and contradicting evidence together.
4. Define confidence in words unless a documented scoring method exists.
5. Add a new row or revision when meaning changes; preserve the old record and link supersession.
6. Mark time-sensitive claims with a review date or event trigger.
7. Never put private customer data, credentials or secrets in a public ledger.
