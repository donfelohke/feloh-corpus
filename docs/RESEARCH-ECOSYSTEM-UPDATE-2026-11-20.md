# Research Ecosystem Update — 2026-11-20

**Status:** RESEARCH / DOCUMENTATION RECONCILIATION  
**Authority:** FELOH Corpus is the shared source of record; specialist repositories own detailed technical research and implementation records.  
**Maturity:** The linked technical work is research/specification unless a repository explicitly provides separate implementation evidence.

## 1. WARENA network, federation and payment research

- [Network, Federation and Payment Architecture](https://github.com/donfelohke/WARENA/blob/main/docs/NETWORK-FEDERATION-AND-PAYMENT-ARCHITECTURE-2026-11-20.md) — GNUnet and alternatives, Reticulum, Pubstrate/ActivityPub, Spritely Goblins/OCapN, GNU Taler, Kenyan mobile-money integration boundaries, threat model, Guix/Shepherd feasibility and qualification plan.
- [Distributed Storage and AFS Comparison](https://github.com/donfelohke/WARENA/blob/main/docs/DISTRIBUTED-STORAGE-AFS-COMPARISON-2026-11-20.md) — OpenAFS cells, volumes, callbacks and security; comparison with NFS, SMB, Ceph, GlusterFS, Syncthing, Tahoe-LAFS, IPFS and local backup.
- [GNU Hurd + Nix compatibility research](https://github.com/donfelohke/WARENA/blob/main/docs/research/gnu-hurd-nix-compatibility-and-cross-build-2026-11.md) — updated with the Guix 1.5.0 / x86_64 Hurd milestone and Childhurd evaluation path.

## 2. Existing desktop, spatial and XR research consolidated

- [WARENA Desktop Architecture](https://github.com/donfelohke/WARENA/blob/main/docs/DESKTOP-ARCHITECTURE.md) — current X11-first policy: X.Org baseline, XLibre compatibility experiment, Gershwin and Guile-WM/WM-NG tracks; Wayland secondary/experimental.
- [Spatial Computing, XR and Opt-in Intelligence Architecture](https://github.com/donfelohke/WARENA/blob/main/docs/SPATIAL-COMPUTING-XR-AI-ARCHITECTURE-2026-11-20.md) — GNU/MAVERIK and DEVA3 historical foundations, spatial services, OpenXR/Monado, graphics, Guix/Shepherd and disabled-by-default opt-in AI.
- [IKAI wearable platform integration](https://github.com/donfelohke/WARENA/blob/main/docs/IKAI-WEARABLE-PLATFORM-INTEGRATION-2026-11-18.md) — WARENA infrastructure responsibilities, Guix/RDE, Guile, Shepherd, IPC, PipeWire, GStreamer, OpenXR and service operations.
- [IKAI XR platform compatibility matrix](https://github.com/donfelohke/WARENA/blob/main/docs/IKAI-XR-PLATFORM-COMPATIBILITY-MATRIX-2026-11-18.md) — native OpenXR, Monado and platform qualification; no deployment claimed.
- [IKAI Mirror technical and scholarly research](https://github.com/donfelohke/Ikai/blob/main/docs/IKAI-MIRROR-TECHNOLOGY-AND-SCHOLARLY-RESEARCH-2026-11-18.md) — IKAI-owned optical and reflective experience research.
- [GENJE kinetics, livecoding and IKAI interaction](https://github.com/donfelohke/Genje/blob/main/docs/KINETICS-LIVECODING-AND-IKAI-INTERACTION-2026-11-18.md) — creative/embodied practice boundary and participant-authored records.

## 3. Clarified technical relationships

1. GNUnet is an alternative-network research system; its November 2026 status identifies GNS as its most mature component while the wider system remains alpha. It is not a production-ready default.
2. Reticulum is evaluated for heterogeneous/off-grid links; it is not presumed interoperable with GNUnet.
3. Pubstrate is a Guile ActivityPub/ActivityStreams implementation, therefore an application/federation-layer research item, not a transport protocol.
4. Spritely Goblins/OCapN concerns distributed objects and capability security; it is not a replacement for a network substrate, database or payment rail.
5. GNU Taler is electronic cash and merchant/exchange infrastructure with conventional bank settlement. Kenyan mobile-money APIs require provider-specific integration and do not automatically satisfy Taler settlement interfaces.
6. OpenAFS is a managed distributed filesystem with cells, volumes and callback-based cache coherence; it is not equivalent to peer-to-peer synchronization or content-addressed storage.
7. GNU/MAVERIK and DEVA3 are historical virtual-environment architecture references. OpenXR/Monado are the contemporary native XR API/runtime qualification track.
8. GNU Hurd's x86_64 support in Guix 1.5.0 is experimental; the package set and hardware support remain far below the operational GNU/Linux baseline.

## 4. Cross-domain ownership

| Domain | Authority | Boundary |
|---|---|---|
| WARENA / CAPABILITY | System architecture, networks, storage, Guix, Shepherd, security and reproducibility | Does not own IKAI participant semantics or NAKEBUSEN transactions |
| IKAI / MIRROR | Reflective experience, participant controls, consent, data meaning and privacy | No diagnosis, identity recognition or behavioural scoring |
| GENJE / EXPRESSION | Creative practice, movement, sound, livecoding and performance provenance | No automated interpretation of performers |
| NAKEBUSEN / ROOT | Sole commercial and transaction interface | Payment automation is not implied by this research |
| FELOH Corpus | Shared definitions, governance, provenance, evidence and navigation | Links to specialist sources rather than duplicating them |

**ONLY NAKEBUSEN TRANSACTS.** No public payment API, checkout flow, STK push, automatic payment verification or website success state is authorized by these research documents.

## 5. Research-to-implementation gates

Before adopting any candidate:
- Pin source revision and licence; verify upstream activity and security advisories.
- Establish target platform, dependencies and Guix package availability.
- Build from pinned sources and preserve logs and hashes.
- Define service identity, permissions, secrets handling, startup/shutdown and recovery.
- Test offline operation, partitions, restore and upgrade.
- Record threat model, data flow, retention and user/participant controls.
- For payment integration, obtain provider approval, settlement semantics and Kenyan legal/compliance review.
- Mark maturity as RESEARCH until reproducible implementation and operational evidence exists.

## 6. GENJE movement notation, generative systems and embodied research

- [GENJE Movement Intermediate Representation and Motion Research (2026-11-20)](https://github.com/donfelohke/Genje/blob/main/docs/GENJE-MOVEMENT-IR-AND-MOTION-RESEARCH-2026-11-20.md) — LaMoGen/LabanLite paper and static source audit; comparison of symbolic, continuous, motion-DSL, diffusion and music-to-dance systems; proposed event-oriented Movement IR; notation/observation/music adapters; African-centred documentation safeguards and staged research roadmap.
- GENJE owns movement, choreography, sound, creative authorship and performance context. IKAI owns participant-facing reflection and privacy; WARENA owns infrastructure and reproducibility; FELOH Corpus owns shared governance and navigation.
- LaMoGen is a research comparator and possible isolated adapter, not GENJE's canonical notation or a selected WARENA runtime. The proposed Movement IR remains a specification; no implementation, capture system, dataset or model deployment is claimed.

## 7. Source and status note

The WARENA documents link to upstream GNUnet, libp2p, Reticulum, Spritely, GNU Taler, CBK, Safaricom, OpenAFS, Ceph, Syncthing, Tahoe-LAFS, IPFS, GNU Guix, GNU Hurd, Debian GNU/Hurd, Monado and historical GNU/MAVERIK material.

Regulatory drafts, provider API availability, package coverage, upstream versions and security advisories are time-sensitive. Revalidate them before implementation or publication as current facts.

**ONE CORPUS · MANY VIEWS · ONE PRACTICE.**
