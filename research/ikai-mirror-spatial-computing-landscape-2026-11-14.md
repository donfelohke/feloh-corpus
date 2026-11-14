# IKAI MIRROR+ — Spatial Computing Research Landscape

**Record date:** 2026-11-14  
**Owner:** FELOH Corpus (cross-project research record)  
**Specialist ownership:** IKAI (reflective/spatial interaction), WARENA (compute/runtime/infrastructure), GENJE (embodied movement and creative expression)  
**Maturity:** RESEARCH / ARCHITECTURE EXPLORATION  
**Decision status:** No hardware bill of materials, platform, runtime, sensor suite, deployment, or product release is approved by this record.

## 1. Executive position

IKAI MIRROR+ should be investigated as an **embodied spatial-computing environment**, not assumed to be a conventional smart mirror with a display hidden behind two-way glass. The mirror may be one optical surface, one interaction surface, or one reflective reference within a larger spatial system. The architecture must be derived from the interaction and perceptual requirements rather than from the familiar consumer smart-mirror form factor.

The central research question is:

> How can a local, human-directed environment connect physical space, reflective representation, spatial content, movement and computation while keeping the participant in control of observation, interpretation, records and action?

The system is not to judge, diagnose, identify, rank, profile or surveil a person. Reflection is not assessment. Sensor availability is not permission to collect data.

## 2. Canonical project boundaries

- **FELOH Corpus:** shared terminology, evidence, provenance, governance and cross-project decisions.
- **IKAI:** reflective interface, spatial interaction, memory, participant-facing experience and research method.
- **WARENA:** hardware integration, operating environment, local compute, graphics/runtime infrastructure, reproducibility, networking and recovery.
- **GENJE:** movement, choreography, livecoding, audiovisual expression and culturally situated embodied practice.
- **NAKEBUSEN:** grounded beauty and loc-care practice; the sole commercial interface. IKAI remains research/WIP and is not a booking or checkout product.

No repository boundary changes are implied.

## 3. Historical software: preserve before replacing

### GNU/MAVERIK

The uploaded paper *GNW/MAVERIK: A micro-kernel for large-scale virtual environments* (Hubbold et al., VRST 1999; DOI: [10.1145/502390.502397](https://doi.org/10.1145/502390.502397)) describes MAVERIK as a publicly available VR system and a micro-kernel for constructing virtual environments. Its design avoids forcing every application into one internal environment representation. It uses application-data callbacks and an object-oriented framework, and addresses large-model processing, custom representations, interaction and navigation. The paper states that GNU/MAVERIK was released as free software under the GNU GPL in February 1999.

The paper places MAVERIK alongside **Deva**, a higher-level operating environment for multi-user, distributed shared environments and persistent concurrent environments. This is a useful architectural separation: rendering/interaction kernel versus higher-level environment and coordination services.

**Disposition:** RESURRECT / EXTRACT as research candidates, not ADOPT. Before any implementation decision, locate and preserve source archives, identify exact release/version and licence texts, inspect build instructions and dependencies, reproduce a build in an isolated environment, and test compatibility with current graphics, compiler and operating-system interfaces. Do not infer current buildability from the paper or from the age of the software.

### DEVA / DEVA3

DEVA-family architecture is relevant to persistent, multi-user, distributed virtual environments and synchronization. The current research discussion treats DEVA3 as a distinct historical architecture worth examining for distributed synchronization and shared-world semantics. The specific DEVA3 primary paper/source has not yet been independently verified in the evidence record for this update.

**Status:** RESEARCH LEAD / SOURCE VERIFICATION REQUIRED. Do not merge claims about DEVA, DEVA3 and MAVERIK into one system or assume source availability.

## 4. Research landscape — technology families

The review must span the complete ecosystem, not only smart mirrors, headsets or consumer XR products.

| Layer | Research questions | Candidate families / examples | Evidence required |
|---|---|---|---|
| Optical and physical surface | Is the reflective surface also a display? What viewing angles, brightness, contrast, glare, privacy and ambient-light conditions apply? | Reflective glass, transparent OLED/LCD, projection, light-field and spatial display approaches | Optical measurements, viewing tests, safety and manufacturability |
| Spatial perception | What space is sensed, at what precision, and for what task? | RGB/depth cameras, stereo, structured light, IMUs, fiducials, AprilTag, OpenCV | Calibration, occlusion, drift, error bounds, data minimisation |
| Spatial registration | How are physical surfaces, body-relative coordinates and virtual objects aligned? | Camera calibration, SLAM, scene graphs, coordinate transforms, ROS 2 TF2 as a reference | Repeatability, latency, relocalisation and failure behaviour |
| Rendering and scene representation | How are large or heterogeneous environments represented and rendered? | MAVERIK archaeology, OpenXR, OpenUSD, Vulkan/OpenGL, scene graphs | Supported features, performance, licence, portability |
| XR runtime and interaction | How are input devices, sessions, spaces and applications coordinated? | OpenXR, Monado and related runtimes | Device support, extension coverage, compositor behaviour, conformance |
| Desktop and application environment | How do ordinary desktop apps coexist with spatial applications? | X11/Wayland, Xpra, display servers, window managers, compositors, remote-app models | Input, focus, clipboard, multi-display, accessibility, recovery |
| Embodied interaction | How does movement become intentional input without becoming a behavioural score? | Laban/Bartenieff-informed analysis, gesture, body tracking, manual controls | Participant interpretation, context, consent, repeatability |
| Audio and multimodal interaction | When do speech, sound or spatial audio add value? | Microphones, beamforming, PipeWire, spatial audio and livecoding systems | Local processing, noise robustness, consent and user override |
| Local compute | Which workloads belong on-device, at edge, or nowhere? | x86-64 and ARM SBCs, GPU/NPU, hardware video decode, Guix | Thermal/power envelope, driver support, reproducible builds, offline operation |
| Distributed environment | What must be shared, synchronized, persistent or federated? | DEVA/DEVA3 research, event logs, local-first sync, peer-to-peer systems | Consistency model, conflict handling, authorization and offline semantics |
| Data, memory and governance | What is recorded, who controls it, and how is it deleted or exported? | Files as authoritative records, SQLite as operational index, provenance ledger | Data-flow map, retention/deletion tests, export and auditability |
| Standards and regulation | Which interface, accessibility, safety, privacy and interoperability standards apply? | Khronos/OpenXR, ISO/IEC, W3C, accessibility and electrical/optical safety standards | Exact standard edition, applicability, implementation and test evidence |
| Industrial R&D | What has been built, deployed, discontinued or patented? | University labs, display vendors, XR manufacturers, automotive/medical/retail research | Primary lab publications, patent status, product lifecycle and independent validation |

This table is a research map, not a list of selected components or claims that each candidate has been tested.

## 5. Architecture hypothesis

A useful decomposition to test is:

1. **Physical environment:** mirror/surface, lighting, room geometry, mounting, power, thermal path and accessibility.
2. **Sensing and input:** optional, task-specific sensors and explicit participant controls.
3. **Spatial model:** calibrated coordinate frames, surfaces, objects and uncertainty.
4. **Interaction runtime:** session lifecycle, input arbitration, navigation, accessibility and application composition.
5. **Rendering pipeline:** scene representation, composition, display output and performance management.
6. **Reflective application:** participant-directed views, annotations, memory and creative tools.
7. **Local data plane:** authoritative files, derived indexes, provenance, retention and export.
8. **Infrastructure plane:** Guix-managed environment, services, backup, recovery, updates and optional networking.
9. **Federation boundary:** opt-in exchange between autonomous nodes only after local operation and authorization are demonstrated.

The layers should be independently replaceable. The mirror surface must not dictate the application model; the XR runtime must not own the participant's records; federation must not be required for local usefulness.

## 6. Research method and decision gates

Use the following dispositions consistently:

- **ADOPT:** evidence shows the component meets a defined requirement and can be maintained.
- **INTEGRATE:** retain an existing component and connect it through a bounded interface.
- **RESURRECT:** recover historical software or hardware because it offers useful capability or architecture.
- **EXTRACT:** preserve a design idea, algorithm, data model or interaction concept without adopting the original system.
- **CREATE:** build only where no suitable, maintainable and rights-compatible component exists.

For every candidate record: exact source and version; author/institution; publication date; licence and rights; source/archive location; build dependencies; supported hardware; runtime interfaces; performance evidence; security/privacy implications; known limitations; maintenance status; reproducibility; and disposition rationale.

A paper, patent, product page, repository, demo video or successful compile is not by itself evidence of an operational IKAI system.

## 7. Explicit non-decisions

This update does **not** approve:
- a two-way-mirror display architecture;
- a headset-first architecture;
- a specific display technology, camera, depth sensor or compute board;
- a production BOM or purchasing list;
- a cloud-dependent architecture;
- face recognition, biometric identity, emotion inference, health diagnosis, scoring or covert recording;
- a deployed mirror, production node, commercial offering or performance claim.

Historical master documents that contain proposed 2026 deployment milestones or production language remain preserved as historical source material. They must not override the current GitHub status: IKAI is RESEARCH / WIP unless implementation evidence is separately reviewed and recorded.

## 8. Immediate research sequence

1. **Source archaeology:** obtain and checksum MAVERIK releases and DEVA/DEVA3 papers or source; verify licence, provenance and dependencies.
2. **Architecture extraction:** map MAVERIK kernel responsibilities separately from DEVA environment, persistence and synchronization responsibilities.
3. **Requirements first:** define IKAI tasks and participant experience before selecting optical or sensing hardware.
4. **Display and optics survey:** compare reflective, emissive, projection and spatial-display configurations under realistic lighting and privacy conditions.
5. **Runtime comparison:** evaluate OpenXR/Monado, desktop compositors and scene-graph approaches against concrete tasks; include non-XR alternatives.
6. **Perception experiments:** begin with synthetic data and fiducials; quantify calibration and tracking error before adding body tracking.
7. **Local prototype:** only after the above gates, build a replaceable bench prototype with documented power, thermal, driver and recovery constraints.
8. **Participant and movement study:** co-design with participants; retain context and authorship; do not convert movement into identity or performance scores.

## 9. Sources and evidence status

- Hubbold, R. et al. *GNW/MAVERIK: A micro-kernel for large-scale virtual environments*. VRST 1999. [ACM DOI 10.1145/502390.502397](https://doi.org/10.1145/502390.502397). **Uploaded PDF inspected; primary paper.**
- DEVA / DEVA3 architecture references discussed in the research conversation. **Primary DEVA3 source not yet independently verified in this record.**
- Existing FELOH Corpus REV008 master material on mirror protocol, reflective/embodied computing, local nodes, federation and semantic ledger. **Historical authorial source; implementation status not inferred.**
- Candidate standards, projects, patents, university and industrial research programmes listed above. **Research targets; not yet individually reviewed or endorsed.**

## 10. Related project records

- [IKAI specialist research record](https://github.com/donfelohke/Ikai/blob/main/docs/IKAI-MIRROR-SPATIAL-RESEARCH-2026-11-14.md)
- [WARENA compute architecture record](https://github.com/donfelohke/WARENA/blob/main/docs/IKAI-MIRROR-COMPUTE-ARCHITECTURE-2026-11-14.md)
- [GENJE embodied interaction record](https://github.com/donfelohke/Genje/blob/main/docs/EMBODIED-SPATIAL-INTERACTION-RESEARCH-2026-11-14.md)
