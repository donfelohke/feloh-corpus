# Ecosystem knowledge map

**Eight core ecosystem repositories + two maintained source forks · one practice**

The FELOH ecosystem has eight practice, enterprise, governance and publication repositories. Two additional repositories maintain focused upstream-derived implementations for WARENA systems research. All ten repositories use `main` as their default branch; repository presence does not imply deployment or release.

```text
feloh-corpus                    ← shared canon, evidence, governance
├── donfelohke.github.io         public website (Locs · Digital)
├── donfelohke                   profile and portfolio navigation
├── NAKEBUSEN                     enterprise operations (only transactor)
├── WARENA                        systems / DIGITAL engineering
├── Genje                         creative / embodied practice
├── Ikai                          reflective-compute research (WIP)
└── Gallery                       approved assets, rights and provenance

WARENA-maintained source forks:
├── dwl-guile                     Guile-configurable Wayland compositor fork
└── home-service-dwl-guile        Guix Home service fork for dwl-guile
```

## Repository responsibilities

| Repository | Responsibility | Maturity boundary |
|---|---|---|
| [feloh-corpus](https://github.com/donfelohke/feloh-corpus) | Shared canon, governance, evidence, glossary and cross-domain indexes | Source of record |
| [NAKEBUSEN](https://github.com/donfelohke/NAKEBUSEN) | Enterprise operations, service catalogue and customer-facing boundaries | Enterprise documentation; availability confirmed per engagement |
| [WARENA](https://github.com/donfelohke/WARENA) | Systems engineering, Guix/RDE configuration, desktop architecture and infrastructure | Research / implementation / deployment must be labelled separately |
| [Genje](https://github.com/donfelohke/Genje) | Genge-rooted creative practice, livecoding, movement and choreohacking | Practice / research; no release implied |
| [Ikai](https://github.com/donfelohke/Ikai) | Reflective-compute, mirror, spatial interaction and XR research | RESEARCH / WIP; not a released product |
| [Gallery](https://github.com/donfelohke/Gallery) | Asset rights, permissions, approval and provenance | Approved assets only |
| [donfelohke.github.io](https://github.com/donfelohke/donfelohke.github.io) | Public NAKEBUSEN website and enquiry paths | Public implementation; deployment verified separately |
| [donfelohke](https://github.com/donfelohke/donfelohke) | Public identity, portfolio and repository navigation | Curated profile |
| [dwl-guile](https://github.com/donfelohke/dwl-guile) | Maintained upstream-derived Guile-configurable Wayland compositor fork | Experimental / secondary research track |
| [home-service-dwl-guile](https://github.com/donfelohke/home-service-dwl-guile) | Guix Home service integration for dwl-guile | WIP; distinct from X11 WM-NG and desktop sessions |

## Domain questions

| Repository | Primary questions |
|---|---|
| Corpus | What do we mean? What is evidenced? What did we decide? |
| NAKEBUSEN | What is offered? How are quality, privacy and customer expectations handled? |
| WARENA | How is a system built, packaged, installed, secured, recovered and verified? |
| Genje | How is a performance, movement score or creative session authored and credited? |
| Ikai | What is hypothesised? What must never be built? How does the participant retain authority? |
| Gallery | Who created or owns this asset? Is it licensed, consented and approved for this use? |
| Website | What should a first-time visitor understand or do next? |
| Profile | Who is the author and where is the project map? |
| dwl-guile | What is upstream-derived compositor behaviour versus WARENA-maintained change? |
| home-service-dwl-guile | How is the compositor configured and operated as a Guix Home service? |

## Current systems research routing

- **WARENA desktop architecture:** [Gershwin Guix packaging plan](https://github.com/donfelohke/WARENA/blob/main/docs/GERSHWIN-GUIX-PACKAGING-PLAN-2026-11.md), [Gershwin upstream delta — 2026-11-18](https://github.com/donfelohke/WARENA/blob/main/docs/GERSHWIN-UPSTREAM-DELTA-2026-11-18.md), and [Guile-WM / WM-NG X11 session audit](https://github.com/donfelohke/WARENA/blob/main/docs/GUILE-WM-WMNG-GUIX-SESSION-AUDIT-2026-11.md).
- **IKAI spatial computing:** [IKAI MIRROR+ research](https://github.com/donfelohke/Ikai/blob/main/docs/IKAI-MIRROR-SPATIAL-RESEARCH-2026-11-14.md) and [WARENA compute architecture](https://github.com/donfelohke/WARENA/blob/main/docs/IKAI-MIRROR-COMPUTE-ARCHITECTURE-2026-11-14.md).
- **GENJE movement and notation:** specialist movement-score and Labanotation research belongs in GENJE; shared sources, terminology and evidence standards belong in this Corpus.
- **Guix Home compositor integration:** `home-service-dwl-guile` remains the Wayland service track. It is not the proposed X11 WM-NG implementation.

These documents record research and architecture decisions, not proof of a successful Guix build, running session, physical IKAI prototype or deployed service.

## Commercial boundary

**ONLY NAKEBUSEN TRANSACTS.**

- NAKEBUSEN is the parent enterprise and the only commercial interface.
- WARENA powers NAKEBUSEN DIGITAL; it is not a competing checkout brand.
- GENJE is creative and cultural practice, not a separate shop.
- IKAI is reflective-compute research, not a product for sale.
- FELOH is the human author and integrated practice.
- Gallery is a rights and approval layer, not an unreviewed public asset feed.

Current approved Eldoret campaign starting prices are Retouch & Styling from KES 700+, Sisterlocs Retie from KES 1,500+, and Artificial Locs Installation from KES 3,500+. Final scope, availability and price must be confirmed directly. An enquiry is not a booking. No braiding or shaving is offered. The authoritative service wording and change-control rules are maintained in the [NAKEBUSEN website service catalogue](https://github.com/donfelohke/donfelohke.github.io/blob/main/docs/SERVICE-CATALOG.md).

## Brand lockup

```text
NAKEBUSEN Locs ° Powered by WARENA
@donfelohke · #HisGenjeness
GRACE · GRIT · GLORY
```

## Evidence and synchronization rules

- `main` is the source of truth for each repository.
- Specialist repositories own domain-specific implementation and research; the Corpus owns shared terms, evidence rules and cross-project decisions.
- Upstream source, Guix package availability, local configuration, successful build, installed host and deployed service are separate states.
- A commit is not a deployment. A PR is not an implementation. A successful CI run is not physical-device validation.
- Label claims with evidence and maturity; use `UNKNOWN` when current evidence is absent.
- Preserve provenance, licensing, consent and human authorship.
- Update cross-repository references when canonical decisions change; do not copy whole documents into every repository.
