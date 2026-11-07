# Cross-Project Desktop Stack Alignment — 2026-11

**Status:** RESEARCH ALIGNMENT / NOT A DEPLOYMENT  
**Authority:** FELOH corpus for cross-domain boundaries; WARENA for technical implementation detail.  
**Rule:** specification ≠ implementation ≠ verification ≠ deployment.

## Decision

WARENA remains the technical source of truth for workstation and desktop-stack experiments. Its current preferred research foundation remains GNU Guix + RDE. Niri + Noctalia v5 is the leading practical Wayland desktop candidate; Sway remains a fallback/comparator; dwl-guile remains experimental. Nix/NixOS is a comparator for declarative system configuration and reproducible builds, not an approved replacement for Guix.

Detailed technical decision and verification matrix: [WARENA — Desktop Stack Decision](https://github.com/donfelohke/WARENA/blob/main/docs/desktop-stack-decision-2026-11.md).

## Domain boundaries

- **WARENA:** owns GNU/Linux, Guix/RDE, Nix/NixOS comparisons, compositor and desktop-shell evaluation.
- **IKAI:** may consume a validated local-first workstation environment; it does not own or claim the desktop platform.
- **GENJE:** may use the workstation for livecoding, audiovisual and movement research; desktop tooling is infrastructure, not cultural identity.
- **NAKEBUSEN DIGITAL:** may offer scoped GNU/Linux and workstation services only when supported by tested compatibility and service evidence.
- **NAKEBUSEN:** remains the only commercial interface. Research stacks are not advertised as shipped products.
- **Gallery:** no desktop-stack dependency; asset rights and approval workflow remain independent.
- **Public website and profile:** may link to the WARENA research record but must not imply deployment or availability.

## Shared status language

Use RESEARCH until a specific configuration has been built and exercised. Use PROTOTYPE only when a runnable implementation exists. Use LIVE only with current host or deployment evidence. A package appearing in a repository is not proof of a working user session, substitute availability, offline completeness or hardware compatibility.

No repo note in this alignment authorizes installation, host mutation, deployment or migration. Human approval is required for those actions.
