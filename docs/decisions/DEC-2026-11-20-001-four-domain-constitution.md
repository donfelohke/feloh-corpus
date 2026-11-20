# DEC-2026-11-20-001 — F3L0H Four-Domain Constitution

- **Date:** 2026-11-20
- **Status:** ACCEPTED · OWNER-DIRECTED
- **Decision owner:** Felix Lwova / Don Feloh
- **Authority:** [F3L0H Sovereign Master Corpus](../FELOH-SOVEREIGN-MASTER-CORPUS-2026-11-20.md)
- **Supersedes:** Conflicting pre-2026-11-20 portfolio/domain hierarchies, including the 2026-10-26 canonical architecture and 2026-10-31 NAKEBUSEN-parent portfolio decision.
- **Implementation scope:** Shared documentation and repository entry points; no native system, hardware, production website source or deployment change is certified by this ADR.

## Question

What is the canonical architecture for the FELOH practice, and how should the four practice domains, supporting repositories, commercial authority and research programme classifications relate?

## Context and evidence

The repository ecosystem had repeated summaries that treated NAKEBUSEN as the parent enterprise and WARENA as a sub-brand or technical identity within NAKEBUSEN DIGITAL. Other summaries grouped Gallery, the profile, the website, GENJE NODE or research programme taxonomies as if they were additional domains. This created conflicting authority and duplicate records.

The owner supplied the F3L0H Sovereign Master Corpus direction on 2026-11-20 and explicitly approved the necessary main-branch documentation changes. The current WARENA Technology Constitution (2026-11-17), IKAI research records, GENJE research records, NAKEBUSEN service catalogue and website Public Facts Register were reviewed as constraints.

## Options considered

1. Retain NAKEBUSEN as parent enterprise and WARENA as a sub-brand.
2. Treat each repository or research programme as a separate domain.
3. Establish F3L0H as the overarching authorship identity with four practice domains and explicit supporting-repository roles.

## Decision

Adopt option 3.

- **F3L0H / FELOH WARENA** is the overarching human authorship, practice and knowledge identity; it is not a fifth practice domain.
- **NAKEBUSEN / ROOT** is grounded physical practice, beauty, heritage, craft and enterprise; it is the only live commercial practice and transaction interface.
- **IKAI / MIRROR** is reflective-computing and embodied spatial research.
- **GENJE / EXPRESSION** is Genge-rooted creative practice, movement, sound, livecoding and choreography.
- **WARENA / CAPABILITY** is sovereign infrastructure, systems engineering, reproducibility and technical enablement.
- **GENJE NODE** is a WARENA manifestation, not a fifth domain.
- Gallery is the asset-rights and provenance repository; the website is the public presentation and release-evidence repository; the profile is author navigation; `dwl-guile` and `home-service-dwl-guile` are supporting WARENA forks. None is an additional practice domain.
- **ONLY NAKEBUSEN TRANSACTS.** Technical capability from WARENA may support NAKEBUSEN service engagements; it does not create a separate transaction interface.
- The twelve-area research programme is a research taxonomy and work plan, not a competing practice-domain architecture.

## Rationale

This model separates authorship, practice, reflective research, creative expression and infrastructure capability without multiplying brands or repositories into artificial organizational domains. It preserves NAKEBUSEN's commercial authority while allowing WARENA to remain a distinct technical capability domain. It also provides a stable home for shared policy while keeping specialist implementation detail in the repository that owns it.

## Consequences

1. The Master Corpus is the shared constitutional source of record.
2. Specialist READMEs and indexes link to the Master Corpus and retain their own domain-specific authority.
3. Historical portfolio documents remain dated evidence and receive supersession notices rather than silent rewrites.
4. Public service facts and payment wording remain in the NAKEBUSEN catalogue and website Public Facts Register; the Master Corpus does not duplicate payment identifiers.
5. WARENA technology policy remains governed by its 2026-11-17 constitution. The desktop baseline is X11-first; Wayland/dwl-guile remains secondary/experimental.
6. Research maturity and implementation status must be stated separately. A commit, document or candidate device is not proof of deployment.
7. Duplicate copies of the NAKEBUSEN variable-subject poster framework are consolidated under the NAKEBUSEN repository.

## Verification

Documentation changes were committed to the main branches of the Corpus, NAKEBUSEN, WARENA, IKAI, GENJE, Gallery, profile and website repositories. Relevant files were fetched again from `main` to confirm that the constitutional markers were present.

No line-by-line audit of every open PR, full internal-link checker, accessibility certification, hardware test, native-system deployment or production website source change is claimed. Remaining unreviewed PRs and implementation evidence are tracked separately.

## Open questions

- Reconcile remaining open research/documentation PRs individually.
- Complete repository-wide internal-link and stale-reference checks.
- Verify exact LinkStar H68K hardware revision, SoC, memory, NICs, wireless, firmware and supported software against the physical unit before qualifying it.
- Verify production website behaviour, accessibility and deployment independently before any release claim.
