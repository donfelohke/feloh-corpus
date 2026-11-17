# Cross-Project Desktop Stack Alignment — 2026-11

**Status:** RESEARCH ALIGNMENT / NOT A DEPLOYMENT  
**Authority:** FELOH Corpus for cross-domain boundaries; WARENA for technical implementation detail.  
**Rule:** specification ≠ implementation ≠ verification ≠ deployment.

## Current architecture direction — 2026-11-17

WARENA's current desktop research is **X11-first**. X.Org is the initial compatibility baseline; XLibre is a drop-in compatibility experiment. The current dual-session architecture direction is:

- **Session A:** Guile-WM — Scheme-native, programmable, keyboard-oriented session.
- **Session B:** Gershwin — GNUstep/OpenStep-inspired application-centred desktop session.

Both are intended as default selectable sessions under one WARENA system identity. This is an architecture decision/research baseline, not evidence that both sessions are installed or deployed on a host. Shared identity and interoperability contracts do not require toolkit or implementation unification.

Wayland remains a secondary/experimental track: dwl-guile with RDE is the primary research path; Sway is a recovery/comparison baseline. Older Niri/Noctalia evaluations are retained as historical research and must not be presented as the current default desktop direction.

Detailed technical records belong in WARENA's [desktop architecture](https://github.com/donfelohke/WARENA/blob/main/docs/DESKTOP-ARCHITECTURE.md) and [technology constitution](https://github.com/donfelohke/WARENA/blob/main/docs/TECHNOLOGY-CONSTITUTION-2026-11-17.md).

## Domain boundaries

- **WARENA:** owns GNU/Linux, Guix/RDE, X11 and desktop/session architecture, compositor and desktop-environment evaluation.
- **IKAI:** may consume a validated local-first workstation environment; it does not own or claim the desktop platform.
- **GENJE:** may use the workstation for livecoding, audiovisual and movement research; desktop tooling is infrastructure, not cultural identity.
- **NAKEBUSEN DIGITAL:** may offer scoped GNU/Linux and workstation services only when supported by tested compatibility and service evidence.
- **NAKEBUSEN:** remains the only commercial interface. Research stacks are not advertised as shipped products.
- **Gallery:** no desktop-stack dependency; asset rights and approval workflow remain independent.
- **Public website and profile:** may link to the WARENA research record but must not imply deployment or availability.

## Shared technology policy

WARENA and IKAI are native-first, libre-first and local-first. JavaScript is prohibited as a language, runtime, framework or dependency; web technologies are excluded as application/runtime architecture. OpenXR is a native API and is distinct from WebXR. See the [FELOH Corpus technology policy](technology-policy-2026-11-17.md).

## Shared status language

Use RESEARCH until a specific configuration has been built and exercised. Use PROTOTYPE only when a runnable implementation exists. Use LIVE only with current host or deployment evidence. A package appearing in a repository is not proof of a working user session, substitute availability, offline completeness or hardware compatibility.

No repo note in this alignment authorizes installation, host mutation, deployment or migration. Human approval is required for those actions.
