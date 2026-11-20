# GitHub ecosystem audit — FELOH / NAKEBUSEN / WARENA

**Date:** 20 November 2026  
**Scope:** Connected account `donfelohke` · public repositories · open PRs · alignment with master synthesis  
**Method:** GitHub API + raw README inspection · documentation only  
**Status:** RESEARCH / AUDIT — no merges or deployments performed by this document

---

## 1. Account inventory

| Field | Value |
|-------|--------|
| Login | donfelohke |
| Public repos (API) | 10 reported on profile; **8** returned by `user:donfelohke` search at audit time |
| Default posture | Documentation- and research-first |

### Repositories verified present

| Repo | Default branch | Open issues (API) | Role |
|------|----------------|-------------------|------|
| donfelohke.github.io | main | 3 | Public website |
| feloh-corpus | main | 18 | Source of record |
| NAKEBUSEN | main | 4 | Enterprise docs |
| WARENA | main | 11 | Systems / stack |
| Ikai | main | 4 | Reflective research |
| Genje | main | 4 | Creative practice |
| Gallery | main | 4 | Asset archive |
| donfelohke | main | 5 | Profile README |

Corpus README map may also list **dwl-guile** and **home-service-dwl-guile** as WARENA research forks; confirm presence on account when operating those tracks.

---

## 2. Public identity alignment (main READMEs)

| Check | Finding |
|-------|---------|
| ONLY NAKEBUSEN TRANSACTS | Present on website repo README and synthesis |
| Lockup Locs ° Powered by WARENA | Present |
| IKAI not a product | Present on Ikai README |
| WARENA not a separate checkout | Present on WARENA README |
| GENJE not a shop | Present on Genje README |
| Evidence / UNKNOWN host rule | Present on Corpus README |
| Text-first site / no Gallery embed | Present on Gallery README |

**Friction points (Pending editorial)**

- Website / i18n strings may still expose **CTO** in founder role line; reconcile with any approved public-title policy.
- Internal governance phrase “ONLY NAKEBUSEN TRANSACTS” is appropriate in docs; keep customer-facing copy focused on enquiry ≠ booking.
- Multiple open research PRs touch indexes — merge order matters to avoid clobbering `docs/README.md` / topic registers.

---

## 3. Open pull-request pressure (sample at audit)

### feloh-corpus (high volume)

Examples open at audit:

| PR | Title (summary) |
|----|-----------------|
| #45 | Reconcile canonical research links · NVIDIA XR AI index |
| #33 | Before Africa sources expansion |
| #32 | Reflective computing + Labanotation brief (draft) |
| #31 | UNESCO General History of Africa framework (draft) |
| … | Additional research/docs PRs remain open |

**Recommendation:** Review newest index-touching PRs first (#45), then historical/source dossiers; avoid parallel merges that rewrite the same navigation files.

### WARENA

| PR | Title (summary) |
|----|-----------------|
| #32 | Cross-link NVIDIA XR AI comparative research |
| #30 | IKAI XR platform compatibility matrix |
| #21 | Foundational CS / UNESCO / Algorave references (draft) |
| #19 | EliteBook sovereign Emacs + Guix workstation setup (draft) |
| … | RDE/dwl-guile, USSD/Taler, and related research PRs historically present |

**Recommendation:** Keep XR and workstation docs as **RESEARCH**; do not promote CANON/LIVE without host + config + recovery evidence.

### donfelohke.github.io

| PR | Notes |
|----|--------|
| #110 | Dependabot upload-artifact 4→7 |
| #5 | Dependabot configure-pages 5→6 |

**Recommendation:** Routine dependency bumps — separate from content redesign. No content redesign PR opened by this audit.

---

## 4. Website (live source posture)

- Live URL: https://donfelohke.github.io/
- Static HTML · theme + language controls · floating dock · Locs / Digital / Connect
- Starting prices and WhatsApp enquiry path present
- Redesign research (18 Nov 2026) recommends **Sovereign Hybrid** visual direction — **not** implemented by this audit

---

## 5. Recommended next GitHub actions (Proposed)

| Priority | Action |
|----------|--------|
| P0 | Human review queue for Corpus #45 and WARENA #30/#32 (index + XR docs) |
| P0 | Do **not** merge redesign or payment UI without explicit authorisation |
| P1 | Land master synthesis (this PR) after editorial pass |
| P1 | Reconcile founder public titles (CTO vs approved list) across site + READMEs |
| P2 | Close or rebase stale draft research PRs that conflict on the same files |
| P2 | Dependabot site PRs after CI green |
| P3 | Gallery: asset approvals before any policy to embed images on the public site |

---

## 6. What this audit did not do

- No file merges to `main`
- No GitHub Pages deployment
- No Guix build or hardware test
- No claim that open PR CI is fully green
- No change to prices, WhatsApp numbers, or payment publication

---

## 7. Companion

[FELOH-MASTER-SYNTHESIS-2026-11-20.md](./FELOH-MASTER-SYNTHESIS-2026-11-20.md)
