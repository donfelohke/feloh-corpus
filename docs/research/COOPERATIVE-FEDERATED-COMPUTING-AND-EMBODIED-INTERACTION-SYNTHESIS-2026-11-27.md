# Cooperative, Federated Computing and Embodied Interaction — Cross-Domain Synthesis

**Date:** 2026-11-27  
**Status:** RESEARCH SYNTHESIS / ARCHITECTURAL QUESTIONS  
**Authority:** FELOH Corpus for cross-domain routing; specialist repositories remain authoritative for their detailed technical and creative records.

## 1. Purpose

This note consolidates the current research conversation across GNU/Linux and GNU/Hurd architecture, Guix and reproducibility, agentic computing, livecoding, spatial XR and reflective interfaces, real-time bidirectional I/O, the Fediverse, and worker-owned cooperative infrastructure.

It is a research map, not a product specification, legal opinion, deployment plan, technology selection, or claim that any proposed service has been implemented.

## 2. Three complementary organizational patterns

The Cathedral, Bazaar and Cooperative are useful as complementary lenses:

- **Cathedral — coherence:** integration discipline, architecture, standards, stewardship, quality assurance and long-term maintenance.
- **Bazaar — distributed innovation:** open participation, independent contributors, experimentation, forks, review, feedback and upstream collaboration.
- **Cooperative — collective sustainability:** shared ownership, member governance, economic participation, accountability and maintenance of common assets.

Working synthesis: **Cathedral for coherence; Bazaar for innovation; Cooperative for sustainability.** This is a proposed organizing framework, not a universal taxonomy or a claim that these models are mutually exclusive.

## 3. Operating-system architecture and service composition

GNU/Linux remains the practical reference environment for current systems work. GNU/Hurd is a distinct research path whose Mach-based microkernel architecture, user-space servers, translators, ports and message-based IPC make service decomposition especially relevant.

The architectural question is whether operating-system responsibilities can be exposed through independently developed, replaceable services with explicit interfaces and authority boundaries.

Research must distinguish:
- kernel and microkernel mechanisms;
- user-space servers and translators;
- device drivers and hardware support;
- IPC, naming and capability mechanisms;
- service supervision and recovery;
- application and ABI compatibility;
- package availability and build reproducibility.

GNU/Hurd's architectural model must not be confused with a claim of Linux feature parity, broad hardware support or production readiness. Guix contributes declarative configuration, functional package management, generations and reproducible environment practices, but GNU/Linux and Hurd support must be checked feature by feature against current upstream evidence.

**Existing technical sources:** [WARENA GNU Hurd and agentic environment study](https://github.com/donfelohke/WARENA/blob/main/docs/AGENTIC-OPERATING-ENVIRONMENT-GNU-HURD-RESEARCH-2026-11-20.md), [Hurd/Guix compatibility research](https://github.com/donfelohke/WARENA/blob/main/docs/research/gnu-hurd-nix-compatibility-and-cross-build-2026-11.md), and [Hurd experiment tracker](https://github.com/donfelohke/WARENA/tree/main/docs/research/hurd).

## 4. Agentic computing and human authority

An agentic environment can compose capabilities such as document retrieval, builds, tests, network inspection, media processing and device control. It must not imply unrestricted administrative authority.

Minimum design questions:
- Who grants authority, for what purpose and duration?
- Which resources and operations are in scope?
- Can actions be previewed, logged, interrupted and reversed?
- What is isolated, and what can persist?
- Which actions require explicit human approval?
- How are secrets, personal data and external services handled?
- Can the system remain useful offline or locally?

Prefer least privilege, capability-oriented access, explicit consent, local execution where feasible, auditability, reproducibility, revocation and human confirmation for consequential actions.

## 5. Real-time I/O, spatial XR and reflective interaction

The physical/digital interface spans capture, transport, processing, synchronization, rendering, output and feedback.

Relevant domains include cameras, depth sensing, displays, GPU/CPU processing, USB/PCIe/Ethernet, audio, haptics, timestamps, clock domains, buffer sharing, spatial tracking and bidirectional control. Throughput alone is insufficient: end-to-end latency, jitter, synchronization, dropped frames, recovery and privacy must be measured.

Linux interface candidates already under study include V4L2, DMA-BUF, DRM/KMS, PipeWire and OpenXR. Their presence in a research stack is not evidence of an integrated or validated pipeline.

IKAI's mirror work treats reflection as a human-facing computing environment, not merely a display mounted behind glass. The M1 two-way-mirror direction remains an engineering hypothesis subject to optical, display, thermal, safety, privacy and usability tests. Cameras and sensors require disclosed purpose, data minimization, local processing where feasible, retention limits and participant control.

**Existing sources:** [WARENA camera/display/I/O research](https://github.com/donfelohke/WARENA/blob/main/docs/CAMERA-DISPLAY-REALTIME-IO-SCALE-RESEARCH-2026-11-24.md), [WARENA current I/O reference update](https://github.com/donfelohke/WARENA/blob/main/docs/research/REALTIME-BIDIRECTIONAL-IO-REFERENCE-UPDATE-2026-11-27.md), [IKAI Mirror research](https://github.com/donfelohke/Ikai/blob/main/docs/IKAI-MIRROR-TECHNOLOGY-AND-SCHOLARLY-RESEARCH-2026-11-18.md), and [IKAI M1 validation](https://github.com/donfelohke/Ikai/blob/main/docs/IKAI-MIRROR-M1-ENGINEERING-VALIDATION-2026-11-18.md).

## 6. Livecoding and embodied creative systems

GENJE's research connects livecoding, sound, audiovisual systems, movement, choreography and choreohacking. This can make computation a real-time expressive practice rather than only a conventional application workflow.

Candidate interoperability areas include Scheme/Guile, TidalCycles, SuperCollider, MIDI, OSC, timecode, movement notation and event-based representations. Each candidate must be evaluated against the actual creative workload, timing requirements, licence, provenance and reproducibility.

Human authorship and performer agency remain primary. Movement or sensor data must not be silently converted into identity, health, emotion, personality or capability claims. Recording, reuse and publication require clear rights, consent, context and provenance.

**Existing sources:** [GENJE livecoding research](https://github.com/donfelohke/Genje/blob/main/docs/TIDALCYCLES-SUPERCOLLIDER-LIVECODING-RESEARCH-2026-11-27.md), [GENJE movement/music interoperability](https://github.com/donfelohke/Genje/blob/main/docs/GENJE-MOVEMENT-MUSIC-INTEROPERABILITY-STUDY-2026-11-20.md), and [GENJE cooperative networks and embodied media](https://github.com/donfelohke/Genje/blob/main/docs/research/GENJE-COOPERATIVE-NETWORKS-AND-EMBODIED-MEDIA-2026-11-23.md).

## 7. Federation is not the same as ownership

Federation enables independently operated services to communicate. It does not, by itself, establish distributed ownership, democratic governance, economic participation or freedom from centralized dependencies.

Examples of distinct protocols and ecosystems include:
- ActivityPub and the Fediverse;
- Matrix and its federation model;
- XMPP and its federation model;
- GNUnet and its peer-to-peer architecture;
- other overlay, mesh and peer-to-peer systems under WARENA evaluation.

Mastodon, PeerTube, Pixelfed, Lemmy, Matrix and XMPP should not be described as one protocol family. Their architectures, moderation models, operational costs, governance and interoperability differ. A federated service may still rely on centralized hosting, identity, funding or administration.

Evaluate each system across protocol openness, operator control, infrastructure ownership, governance, moderation, portability, privacy, resilience and sustainability.

## 8. Independent workers and federated cooperatives

A federated cooperative model is a hypothesis for enabling independent workers and separate worker-owned organizations to share infrastructure without surrendering their own autonomy.

Possible shared capabilities include hosting, connectivity, identity, communications, storage, backup, software collaboration, training, procurement, accounting and collective support.

Keep these boundaries explicit:
1. Individual members retain control of their own work and personal data.
2. Each cooperative governs its membership, assets and internal decisions.
3. Shared infrastructure is governed by documented agreements and accountable operators.
4. Federation between cooperatives does not automatically transfer ownership or decision rights.
5. Costs, maintenance, liability, dispute resolution, succession and exit/portability must be designed rather than assumed.

This note does not prescribe a Kenyan legal form or assert compliance with cooperative, employment, data-protection, tax, payment or communications law. Any operational model requires Kenya-specific legal, financial, member and community research.

## 9. Research work packages and ownership

| Work package | Lead repository | Next evidence |
|---|---|---|
| GNU/Hurd service model and hardware feasibility | WARENA | Upstream status, package coverage, hardware matrix, reproducible experiments |
| Guix reproducibility and service supervision | WARENA | Pinned channels, build records, rollback and recovery tests |
| Human-governed agent capabilities | WARENA | Threat model, permissions, audit log, revocation and approval tests |
| Federation and self-hosted infrastructure | WARENA | Protocol comparison, operational cost, security and interoperability tests |
| Real-time camera/display/I/O | WARENA | Measured latency, jitter, synchronization, throughput and failure recovery |
| Mirror and spatial interaction | IKAI | Optical M1 bench tests, participant protocol, data-flow and privacy validation |
| Livecoding and movement interoperability | GENJE | Reproducible creative sessions, timing/format round trips, rights and provenance |
| Cooperative ownership and federation governance | FELOH Corpus | Member research, governance alternatives, Kenyan legal and economic review |

## 10. Decision discipline

Apply the existing WARENA and Corpus evidence vocabulary. Distinguish documented, researched, proposed, prototyped, tested, deployed and live-verified states. A technology appearing in a comparison is not a selection. A protocol specification is not proof of interoperability. A repository document is not implementation evidence.

Follow the existing **Do Not Recreate Wheels** policy: identify mature projects, standards, scholarship and proven components first; reuse, adapt and interoperate where suitable; credit upstream creators; document any evidenced gap before proposing new implementation.

## 11. Cross-project boundaries

- **WARENA** owns systems engineering, operating environments, networking and infrastructure research.
- **IKAI** owns reflective-computing, mirror, spatial interaction and participant-privacy research.
- **GENJE** owns creative computation, livecoding, movement, music and embodied expression.
- **FELOH Corpus** owns shared identity, governance, provenance, cross-domain routing and research coordination.
- **NAKEBUSEN** remains the ROOT enterprise and sole commercial transaction interface. Research collaboration does not change that boundary.

The practices are distinct and interoperable; this synthesis does not create a new product, subsidiary, repository or commercial checkout.

---

**Working synthesis:** Cathedral for coherence. Bazaar for innovation. Cooperative for sustainability. Human authority across the system. Open interfaces between its parts. Evidence before claims.
