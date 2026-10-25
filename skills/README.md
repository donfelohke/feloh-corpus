# FELOH Conversation-Derived Skill Pack

Version: 0.1.0  
Status: PROPOSED — review before adoption  
Canonical source: https://github.com/donfelohke/feloh-corpus

This pack turns repeated instructions, decisions and working practices from FELOH conversations into portable agent-skill definitions. Each skill is an independent directory with a SKILL.md entry point.

## Skills

| Skill | Primary responsibility |
|---|---|
| [FELOH Canon Keeper](./feloh-canon-keeper/SKILL.md) | Canon, terminology, decisions and evidence |
| [NAKEBUSEN Operator](./nakebusen-operator/SKILL.md) | Business operations, services, pricing and customer-facing content |
| [WARENA Systems Engineer](./warena-systems-engineer/SKILL.md) | Reproducible, local-first systems |
| [IKAI Researcher](./ikai-researcher/SKILL.md) | Reflective-compute research, privacy and human authorization |
| [GENJE Choreohacker](./genje-choreohacker/SKILL.md) | Genge, livecoding, movement and creative provenance |
| [Sovereign Repository Steward](./sovereign-repository-steward/SKILL.md) | GitHub structure, pull requests, CI, security and release verification |

## Shared operating contract

1. Read the relevant canonical source before proposing changes.
2. Preserve explicit user constraints, names, spelling, prices, boundaries and decisions.
3. Distinguish CONCEPT, RESEARCH, PROTOTYPE, LIVE, HISTORICAL, SUPERSEDED, UNKNOWN and NOT VERIFIED.
4. Never describe a proposed change as completed until the relevant tool confirms it.
5. Prefer focused changes, reviewable diffs, tests and pull requests over broad unreviewed writes.
6. Protect secrets, credentials, private customer data and sensitive personal context.
7. Keep humans responsible for consequential approvals, merges, transactions and publication.
8. State uncertainty and identify the evidence needed to resolve it.
9. Skills are instructions, not proof of capability, access, compliance or deployment.
10. Installing a skill does not grant repository access or external-app permissions.

## Installation

These files follow the portable Agent Skills convention: a directory containing SKILL.md with YAML frontmatter containing name and description. Adapt and install them through each target platform's currently supported mechanism. This repository commit alone does not install them into ChatGPT, GitHub Copilot, Grok or another agent.

## Change control

Treat each skill as versioned operational policy. Propose changes through pull requests. Record the reason for material changes and check them against the corpus, governance and user constraints before merging.

## Known limitations

This first draft is synthesized from conversation context and the existing corpus. Platform-specific tool names and permission models are intentionally not hard-coded. Test each skill against representative tasks before treating it as production-ready. A skill's existence does not prove its described workflow is implemented.
