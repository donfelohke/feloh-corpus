# Research Ecosystem Update — 2026-11-18

**Status:** RESEARCH / DOCUMENTATION UPDATE  
**Authority:** FELOH Corpus is the shared source of record; specialist repositories own their detailed research and implementation domains.

## New specialist research records

| Domain | Canonical location | Scope | Maturity |
|---|---|---|---|
| NVIDIA XR AI comparison | [NVIDIA XR AI comparative study](https://github.com/donfelohke/Ikai/blob/main/docs/NVIDIA-XR-AI-ARCHITECTURE-COMPARATIVE-STUDY-2026-11-18.md) | Four-plane architecture, participant-scoped media, typed model interfaces and process lifecycle; reference only | RESEARCH |
| IKAI voice and smart glasses | [IKAI distributed architecture](https://github.com/donfelohke/Ikai/blob/main/docs/IKAI-VOICE-GLASSES-DISTRIBUTED-ARCHITECTURE-2026-11-18.md) | Voice-only and visual AR wearables; hybrid local/remote intelligence; first-class display; contracts, hardware qualification, Scheme integration, threat model and staged MVP | RESEARCH |
| WARENA integration | [IKAI wearable platform integration](https://github.com/donfelohke/WARENA/blob/main/docs/IKAI-WEARABLE-PLATFORM-INTEGRATION-2026-11-18.md) | Guix/RDE, Guile, Shepherd, SQLite, IPC, PipeWire, GStreamer, OpenXR and service operations | RESEARCH |
| GENJE kinetics/livecoding | [Kinetics, Livecoding & Reflective Interaction](https://github.com/donfelohke/Genje/blob/main/docs/KINETICS-LIVECODING-AND-IKAI-INTERACTION-2026-11-18.md) | Movement, kinetics, choreography, notation, algorithmic music, synchronised performance streams and participant authorship | RESEARCH / PRACTICE FRAMEWORK |
| IKAI mirror | [Mirror technology and scholarly research](https://github.com/donfelohke/Ikai/blob/main/docs/IKAI-MIRROR-TECHNOLOGY-AND-SCHOLARLY-RESEARCH-2026-11-18.md) | Optical mirror engineering, AR mirror approaches and scholarly reading | RESEARCH |

## Canonical architecture decisions

- IKAI explores reflective computing; it is not a released product or checkout brand.
- IKAI's wearable scope includes both voice-only and visual AR devices.
- Intelligence placement is hybrid, with local control and sensitive processing preferred; remote inference is optional, explicit and purpose-bound.
- The display is a first-class interaction surface, not a decorative accessory.
- WARENA owns infrastructure, Guix/RDE configuration and operational integration; it does not own IKAI's participant semantics.
- GENJE owns creative and embodied practice; it does not provide automated interpretation of performers.
- FELOH Corpus owns shared definitions, evidence rules, provenance and cross-domain navigation.
- NAKEBUSEN remains the only commercial interface. No new product, service, booking path or public claim follows from these research notes.

## Shared technical policy

The research is constrained by WARENA's native-first, libre-first, local-first technology direction. GNU Guile/Scheme governs policy and orchestration. GNUstep/Objective-C, native graphics and sensing APIs, OpenXR, PipeWire, GStreamer, SQLite, Unix sockets and Shepherd are candidates subject to licence, source, hardware and build qualification. JavaScript is not an allowed runtime or application dependency; WebXR is not the selected XR route.

A candidate upstream repository is not a selected dependency. A README is not a successful build. A build is not a tested device integration. A prototype is not a deployment.

## Evidence and maturity controls

- Hardware names are candidates until exact model/revision, firmware, developer API and privacy behaviour are tested.
- TAM figures are scenario estimates until category definitions and source assumptions are reconstructed; do not present them as an IKAI forecast or valuation.
- Speech, vision and spatial inference must not become identity, emotion, health, personality or capability scoring.
- Raw audio/video and spatial data are not retained by default.
- Participant consent, inspectability, export, correction, deletion and stop controls are release gates.
- GENJE movement records remain contextual, authored and rights-aware; notation does not reveal inner state.
- No new repository is created. WARENA remains the configuration home; existing forks remain separate.

## Review and maintenance

These records should be reviewed against specialist repositories before any future merge or public release. Update the master topic register, documentation tree and specialist knowledge-base indexes when the draft changes are accepted. Keep all new work labelled RESEARCH until implementation evidence exists.
