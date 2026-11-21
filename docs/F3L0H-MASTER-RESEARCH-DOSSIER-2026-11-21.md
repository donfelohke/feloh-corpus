# F3L0H Master Research Dossier

**Document ID:** F3L0H-MRD-2026-11-21  
**Status:** RESEARCH · Source-discovery baseline · Not implementation  
**Date:** 21 November 2026  
**Parent constitution:** [F3L0H Sovereign Master Corpus](./F3L0H-SOVEREIGN-MASTER-CORPUS-2026-11-20.md)  
**Domain map:** [Four domains](./DOMAIN-MAP-FOUR-DOMAINS-2026-11-20.md)

**Central question:** How can people create, care for, compute, move, communicate, preserve knowledge and operate infrastructure while retaining meaningful control over the systems they depend on?

**Engineering principle:** Do Not Recreate Wheels — identify prior art, reuse what works, credit creators, innovate only where a demonstrable gap remains.

**Evidence posture:** This dossier synthesises research directions and cited discovery leads. A link is not proof that every passage has been exhaustively reviewed. A committed document is not proof that the technology works. Markdown is not deployment evidence.

---

## 1. Domain interdependence

| Domain | Research subject | Main question |
|--------|------------------|---------------|
| **NAKEBUSEN · ROOT** | Loc care, beauty craft, livelihood, trust | How does a real, locally grounded practice remain excellent, viable and governed? |
| **IKAI · MIRROR** | Reflective environments, optics, sensing, memory | How can an environment reflect without becoming surveillance? |
| **GENJE · EXPRESSION** | Genge, music, movement, livecoding | How can embodied cultural expression be created and transmitted without stripping context? |
| **WARENA · CAPABILITY** | GNU/Linux, Guix, embedded, networks, energy | How can infrastructure stay inspectable, reproducible, repairable and human-controlled? |
| **FELOH Corpus** | Knowledge, provenance, governance | How do decisions, sources, rights and evidence remain traceable? |

**Shared governance model (conceptual):**  
Observe → Record → Reflect → Form intent → Authorise → Act → Evaluate → Preserve.

This is a research and governance model, **not** a claim that all domains implement one integrated system.

**GENJE NODE** remains nested under **WARENA** (technical manifestation), not a fifth domain.

---

## 2. Prior art (discovery leads — not completed literature reviews)

| Area | Lead | Implication for F3L0H |
|------|------|------------------------|
| Smart mirrors + privacy | 2025 open-access work on smart mirrors and data-protection regulation | Privacy is an engineering requirement, not an afterthought |
| Display optics | Display reflection research (ambient + emitted light) | Optical design is primary for any IKAI mirror |
| Dance notation | Labanotation; Motif; LMA (Ohio State dance resources) | Notation already exists — do not reinvent without gap analysis |
| Notation + preview | LabanLab (2025) | Interactive notation–movement tools exist |
| Motion → notation ML | 2026 Scientific Reports hybrid Transformer–LSTM on benchmarks | Benchmark success ≠ all dance traditions |
| Markerless capture | FreeMoCap; OpenCap (non-commercial research terms for OpenCap) | Prefer open local capture before proprietary stacks |
| Livecoding music | TidalCycles | Strong GENJE music candidate |
| Visual synth | Hydra (docs repo archived Jan 2024) | Evaluate separately; avoid silent architectural dependency |
| Reproducible science | Guix + Software Heritage (Scientific Data) | Supports WARENA reproducibility thesis |
| Vehicle software | AGL SoDeV; Eclipse OpenBSW; EVerest; SocketCAN; Zephyr | EV research must separate app Linux from safety-critical control |
| E-mobility / energy | Uganda solar microgrid + e-two-wheelers; Nairobi batteryscape | Energy + mobility + storage as one system |
| Kenya policy | National Electric Mobility Policy (Mar 2026); EPRA charging guidelines; KRA eTIMS; ODPC / Data Protection Act 2019 | Compliance and infrastructure context for ROOT and WARENA |

---

## 3. Domain research packages

### 3.A NAKEBUSEN · ROOT — RESEARCH

**Primary evidence** is service quality, customer experience, commercial records and local reputation — not website copy alone.

**Preserve established catalogue facts (verify before public change):**

| Service | Starting price |
|---------|----------------|
| Retouch & Styling | KES 700+ |
| Sisterlocs Retie | KES 1,500+ |
| Artificial Locs Installation | KES 3,500 |

No invented categories, no braiding, no unconfirmed nail-service claims on public surfaces without catalogue approval.

**Open investigations:** Eldoret/Uasin Gishu permits · cost/time/margin · demand · hygiene SOPs · consent and record retention · eTIMS practical path · ODPC controller/processor obligations for photos and contacts.

**Direction:** Study as a real service enterprise first; technology supports, does not redefine the business.

### 3.B IKAI · MIRROR — RESEARCH

Separate three layers:

1. **Mirror** — optical/physical reflective surface  
2. **Instrument** — cameras, displays, illumination, sensors  
3. **Reflective environment** — software/interaction model  

**Conceptual REFLECTION± model:** LIGHT IN → OBSERVATION + COMPUTE → LIGHT OUT.

**Open investigations:** M1 optical specs · glass selection · camera/display placement · latency · privacy-preserving retention · minimal semantic schema (observation, reflection, intent, action).

**Starting internal doc:** IKAI mirror research / cross-project alignment (2026-11-18) — extend, do not restart from zero.

### 3.C GENJE · EXPRESSION — RESEARCH

**Precise research question:** How can an African-centred movement vocabulary coexist with established notation and motion-capture systems without forcing movement into an inadequate representation?

**Prior systems to study:** Labanotation · Motif · LMA · FreeMoCap · OpenCap · TidalCycles · SuperCollider.

**Open investigations:** Local movement ontology · notation choice · music–movement sync · capture accuracy in performance · consent and ownership · offline tools · **GENJE NODE** as portable creative runtime under WARENA.

### 3.D WARENA · CAPABILITY — RESEARCH

**Direction (not validated deployment):** Guix manifests + pinned channels · Guile programmability · RDE research track · native Linux · local storage/services · inspectable builds.

**Sovereign Movement Systems (cross-domain opportunity):** energy · compute · EV/nduthi/matatu · local network · human governance. Research architecture only.

**Open investigations:** EV SDK/CAN/charging interoperability · battery ownership/repair · swap vs fixed charge · solar/portable storage · county infrastructure · virtual-first vehicle software testing before physical experiment.

**Hard boundary:** Experimental Linux applications must not be confused with safety-critical vehicle control.

### 3.E FELOH Corpus — GOVERNANCE

| Status | Meaning |
|--------|--------|
| ESTABLISHED | Reliable sources or demonstrated evidence |
| RESEARCH | Under investigation |
| PROPOSED | Candidate design |
| IMPLEMENTED | Present in repo or working system |
| VALIDATED | Tested against stated acceptance criteria |
| UNKNOWN | Insufficient evidence |

A documentation CI pass is not hardware validation.

---

## 4. Cross-domain connections

| Connection | Research question |
|------------|-------------------|
| NAKEBUSEN × IKAI | Reflective support for presentation without invasive capture? |
| NAKEBUSEN × WARENA | Affordable local-first digital support for a beauty enterprise? |
| IKAI × GENJE | Reflect movement/rhythm with accountable representation? |
| IKAI × WARENA | Native local privacy-preserving real-time IO architecture? |
| GENJE × WARENA | Portable compute/energy for livecoding and performance? |
| GENJE × Corpus | Attribution, consent, cultural IP for movement and works? |
| WARENA × Corpus | Reproducible docs for software, hardware, decisions? |
| WARENA × ROOT | Energy/compute/mobility for livelihoods? |

**Three propositions (RESEARCH):**

1. **Reflection±** — light, observation, computation, interpretation, output as one system (IKAI foundation).  
2. **Sovereign Movement Systems** — energy, vehicles, infrastructure, computation, mobility (WARENA-led).  
3. **Embodied Computing** — movement as input with accountability to person and community (IKAI–GENJE boundary).

---

## 5. Priority work packages

| ID | Package | Intent |
|----|---------|--------|
| **P0** | Corpus and evidence reconciliation | Verified index of existing work, sources, ownership, licensing, status |
| **P1** | WARENA systems and reproducibility | Guix/RDE, native Linux, embedded, networks, open vehicle stacks — what builds |
| **P2** | IKAI optical and real-time IO | Optical spec, system diagram, measurement and latency protocols |
| **P3** | GENJE movement and creative tech | Notation, capture, livecoding; culturally accountable representation |
| **P4** | Sovereign Movement Systems | Kenya EV policy, nduthi/matatu, power, charging, software, counties |
| **P5** | NAKEBUSEN operational research | Economics, CX, compliance, records, practical tech needs |

---

## 6. Evidence register (starter)

Preserve and deepen investigation of:

- ODPC — Data Protection Laws / guidance  
- KRA — eTIMS  
- Smart mirrors and data protection regulation (2025 chapter)  
- Evaluating display reflections (optics literature)  
- Ohio State — Dance Research Resources (Labanotation / Motif / LMA)  
- FreeMoCap · OpenCap  
- LabanLab — Eurographics 2025  
- Scientific Data — Guix reproducible research  
- GNU Guile manual  
- AGL SoDeV · Eclipse OpenBSW · EVerest  
- Kenya National Electric Mobility Policy · EPRA charging/battery-swap guidance  
- East African solar microgrid + e-mobility study · Nairobi batteryscape research  
- TidalCycles documentation  

Full bibliographic entries with access dates and claim-level citations belong in specialist bibliographies and the claim register — not only this overview.

---

## 7. Required structure for future domain reports

Each domain report should include:

1. Problem and research questions  
2. Prior art, standards, upstream projects and licences  
3. Technical boundaries  
4. African / Kenyan context  
5. Cost, energy, hardware, operations  
6. Privacy, safety, cultural rights, governance  
7. Gaps  
8. Proposed experiments and acceptance criteria  
9. References, provenance, status labels  

---

## 8. Explicit non-claims

- Not every source above has been line-read end-to-end in this pass.  
- No repository implementation or hardware procurement is authorised by this document.  
- No LIVE status for IKAI mirror, GENJE NODE, Sovereign Movement Systems, or full RDE desktop.  
- Website and commercial catalogue changes require separate approval.  

---

## 9. Next actions

1. **P0** — reconcile this dossier against existing Corpus files (`claim-register.md`, `annotated-source-starter.md`, IKAI/WARENA specialist docs).  
2. Open specialist domain reports under `research/` or domain repos with claim-level citations.  
3. Gate any engineering spike with acceptance criteria and host evidence fields (`UNKNOWN` until proven).

**FELOH generates. NAKEBUSEN grounds. IKAI reflects. WARENA enables. GENJE embodies.**

*End of Master Research Dossier v0 — living RESEARCH baseline.*
