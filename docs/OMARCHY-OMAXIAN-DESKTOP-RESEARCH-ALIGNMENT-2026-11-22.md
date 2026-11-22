# Cross-repository desktop architecture research alignment — 2026-11-22

**Owner:** FELOH Corpus (shared definitions, evidence and repository routing)  
**Technical source of record:** [WARENA — Omarchy, Omaxian and the Reproducible Desktop](https://github.com/donfelohke/WARENA/blob/main/docs/OMARCHY-OMAXIAN-GUIX-DESKTOP-ARCHITECTURE-RESEARCH-2026-11-22.md)  
**Status:** RESEARCH / CROSS-REPOSITORY DOCUMENTATION AUDIT  
**Scope:** Ten existing repositories; documentation-only; no implementation or deployment claim.

## 1. Shared conclusion

WARENA's research question is whether one user-controlled computing environment can combine:

- Omarchy's coherent, opinionated desktop experience;
- GNU Guix's declarative configuration, generations and provenance;
- native GNU/Linux extensibility through replaceable components and documented interfaces.

The conclusion is **architecturally feasible as a research objective, not yet demonstrated as a WARENA implementation**. WARENA remains the technical owner of this investigation. The Corpus records the cross-project conclusion and routes readers to WARENA's detailed analysis; it does not duplicate the technical study.

## 2. Shared evidence and policy boundaries

- Omarchy v4.5.0 is the official release checked for this record (published 2026-11-05). Its release notes report over 740 merged pull requests, more than 180 contributors in twelve weeks, a traditional desktop mode alongside tiling, Apple Silicon support and 50 languages. These are project-reported release figures, not active-user or retention measurements.
- Omarchy Quattro's v4.0.0 release documents consolidation of desktop-shell functions into Quickshell.
- Quickshell describes itself as a QtQuick/QML toolkit with integrations for desktop-shell functions. Its architecture is a useful case study, not an approved WARENA dependency.
- Omaxian's official repository documents an Omarchy-shell port for Debian-family systems with X11/XLibre and i3. Its latest release endpoint returned v1.2.2 (2026-11-16); the project retains Quickshell/QML and makes X11-specific adaptations.
- GNU Guix documents declarative system configuration, generations, channel revision inspection and rollback. These facilities do not replace backups of mutable user data or prove a WARENA host is reproducible.
- WARENA's existing Technology Constitution remains authoritative: native-first, libre-first, local-first, user-controlled; JavaScript and web technologies are prohibited as WARENA system/application architecture.
- WARENA's existing desktop policy remains X11-first: X.Org baseline, XLibre separate compatibility experiment, Gershwin and Guile-WM / WM-NG X11 research tracks; Wayland/dwl-guile remains secondary and experimental.

## 3. Repository ownership and disposition

| Repository | Disposition for this research | Reason |
|---|---|---|
| WARENA | **Canonical technical study** | Owns desktop architecture, Guix/RDE configuration and systems engineering |
| feloh-corpus | This cross-repository alignment and evidence routing | Owns shared definitions, evidence standards and repository map |
| dwl-guile | Add a concise architecture-boundary pointer | Clarifies that its Wayland fork remains experimental and is not the X11 desktop track |
| home-service-dwl-guile | Add a concise architecture-boundary pointer | Clarifies Guix Home service scope and experimental Wayland status |
| Ikai | No content change required | Mirror/reflective-computing research is not redefined by a desktop-shell case study |
| Genje | No content change required | Creative/embodied practice remains distinct from WARENA desktop engineering |
| NAKEBUSEN | No content change required | Commercial services, customer terms and service facts are outside this technical study |
| Gallery | No content change required | Asset rights, provenance and approval are outside this technical study |
| donfelohke.github.io | No content change required | Public customer-facing website should not inherit internal desktop research |
| donfelohke | No content change required | Public identity and portfolio navigation remain unchanged |

“No content change required” is a deliberate scope decision, not an assertion that those repositories were modified. Existing 2026-11-22 ecosystem updates in the specialist repositories remain the relevant domain records.

## 4. No architectural decision is silently changed

This research does not:
- approve Quickshell, QML, JavaScript or a new UI runtime for WARENA;
- select a monolithic shell or implement a new modular shell;
- change the X11-first desktop policy or select a new window manager;
- promote dwl-guile or its Home service beyond experimental status;
- establish a WARENA build, prototype, host, hardware validation, release or deployment;
- create a new repository or duplicate the technical report into every domain.

The WARENA report recommends investigating modular native components coordinated through documented interfaces and a Guile/Scheme-oriented integration layer. Existing standards and upstream components should be reused where suitable. New frameworks or protocols require an evidenced gap.

## 5. Evidence vocabulary

Use the shared maturity distinctions:

- **RESEARCH:** source review, comparison or hypothesis.
- **SPECIFICATION:** documented intended design and acceptance criteria.
- **IMPLEMENTED:** code or configuration exists in the identified repository/commit.
- **TESTED:** recorded test execution with environment, result and limitations.
- **RELEASED:** identifiable published artifact/version.

A source repository or upstream release does not prove WARENA compatibility. A documentation commit is not implementation. A successful build is not a graphical, hardware, recovery or deployment test.

## 6. Primary sources

- Omarchy v4.5.0: https://github.com/omacom/omarchy/releases/tag/v4.5.0
- Omarchy Quattro v4.0.0: https://github.com/omacom/omarchy/releases/tag/v4.0.0
- Quickshell: https://quickshell.org/about/
- Omaxian: https://github.com/aozora/omaxian
- Omaxian v1.2.2: https://github.com/aozora/omaxian/releases/tag/v1.2.2
- GNU Guix manual: https://guix.gnu.org/manual/en/
- RDE upstream: https://github.com/abcdw/rde
- WARENA technical study: https://github.com/donfelohke/WARENA/blob/main/docs/OMARCHY-OMAXIAN-GUIX-DESKTOP-ARCHITECTURE-RESEARCH-2026-11-22.md

**Review record:** GitHub repository trees and selected documentation were inspected across all ten existing repositories on 2026-11-22. Detailed technical source review is recorded in WARENA. This is not a complete line-by-line audit of every file in all repositories.
