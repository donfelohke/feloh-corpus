# Decision and Provenance Protocol

## Purpose

This protocol keeps canonical claims, decisions, revisions, and implementation status traceable. It is a repository-level baseline and does not replace the full SEQ-07 specification if that exists elsewhere in the canonical corpus.

## Evidence chain

Use this chain when it fits the claim:

**CLAIM → DOCUMENT → IMPLEMENTATION → OBSERVATION → RECORD → ATTESTATION → SEQ-07**

Not every conceptual claim has an implementation. If a stage does not exist, record that fact instead of inventing an artifact.

## Minimum record for a material decision

- **ID:** stable identifier, if one is assigned.
- **Date:** date of the decision or proposal; use an explicit unknown if not known.
- **Status:** proposal, accepted, rejected, superseded, or unresolved.
- **Claim or question:** concise statement of what is being decided.
- **Context:** why the question matters.
- **Options considered:** include material alternatives where known.
- **Decision and rationale:** what was accepted and why; do not fabricate consensus.
- **Evidence:** source documents, commits, tests, observations, or attestations.
- **Consequences:** affected projects, documents, interfaces, and users.
- **Supersedes / superseded by:** preserve the lineage of changed positions.
- **Open questions:** what remains uncertain.

## Status discipline

Use these labels for the maturity of a claim or artifact:

- **LIVE**
- **PROTOTYPE**
- **RESEARCH**
- **CONCEPT**
- **HISTORICAL**
- **SUPERSEDED**
- **UNKNOWN**

These labels describe different states, not a quality ranking. Record the evidence and date behind a status where material.

## Rules

1. **ATTESTATION SPECIFIED ≠ EXECUTED.** A defined test, policy, workflow, or attestation is not proof that it ran.
2. **Implementation is proof.** Where a claim depends on behavior, point to the code, execution record, test output, observation, or operational evidence that supports it.
3. Separate user-provided canon from external facts, interpretation, and assistant-generated proposals.
4. Preserve contradictory historical statements with dates and status labels; do not erase the conflict without an explicit decision.
5. A commit proves that text or code was committed; it does not by itself prove the described system works.
6. If evidence is missing, use **UNKNOWN** and name the evidence needed to resolve it.
7. When a decision changes a canonical relationship or boundary, update relevant indexes and views.

## Suggested decision file

A future decision record can use this template:

```markdown
# DEC-YYYY-NNN: Short title

- Date:
- Status: PROPOSED
- Decision owner / participants:
- Related documents:
- Supersedes:
- Superseded by:

## Question

## Context and evidence

## Options considered

## Decision and rationale

## Consequences

## Verification

## Open questions
```

## Current repository status

This protocol is **LIVE as documentation**. No claim is made here that an external decision ledger, automated attestation service, or SEQ-07 enforcement workflow has been deployed.
