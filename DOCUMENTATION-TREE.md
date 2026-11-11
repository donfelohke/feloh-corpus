# FELOH / NAKEBUSEN — Complete documentation tree

**Status:** CANONICAL ARCHITECTURE · Updated 11 November 2026  
**Owner of this map:** feloh-corpus  
**Rule:** One source of truth per fact · conceptual plan ≠ implemented system · ONLY NAKEBUSEN TRANSACTS

This file is the master hierarchy for governance, research, culture, business, technology, websites, and archives. Specialist repositories hold operational detail; they must link here for shared definitions and must not redefine brand constitution or service prices without a corpus PR.

---

## 0. How to use this tree

| Label | Meaning |
|-------|--------|
| **LIVE** | Exists on default branch and is treated as current guidance |
| **PARTIAL** | File or section exists; incomplete or needs editorial pass |
| **PLANNED** | Filename and ownership agreed; content not yet written |
| **EXTERNAL** | Lives outside GitHub (e.g. social profiles) |

When two files disagree: **brand and prices → corpus / NAKEBUSEN service catalogue**; **site behaviour → donfelohke.github.io**; **systems runbooks → WARENA**; **assets → Gallery**.

---

## 1. Ecosystem map (repositories)

| Repo | Role | Doc ownership |
|------|------|----------------|
| [feloh-corpus](https://github.com/donfelohke/feloh-corpus) | Canon, evidence method, brand constitution, skills | Shared definitions |
| [donfelohke.github.io](https://github.com/donfelohke/donfelohke.github.io) | Public website + site ops docs | Webcopy, design standards, deployment |
| [NAKEBUSEN](https://github.com/donfelohke/NAKEBUSEN) | Enterprise / commerce domain | Service catalogue, webcopy research |
| [WARENA](https://github.com/donfelohke/WARENA) | Systems engineering | Implementation handbooks, stack |
| [Gallery](https://github.com/donfelohke/Gallery) | Visual archive (linked, never embedded on site) | Manifest, provenance, rights |
| [Genje](https://github.com/donfelohke/Genje) | Creative / Genge practice | Creative notes (maturity-labelled) |
| [Ikai](https://github.com/donfelohke/Ikai) | Reflective-compute research | Research docs only; not a product |
| Profile `donfelohke/donfelohke` | GitHub profile README | Global intro (if present) |

---

## 2. Root tree (proposed + existing)

```
feloh-corpus/                          # CANON HOME
├── DOCUMENTATION-TREE.md              # THIS FILE · LIVE
├── README.md                          # LIVE
├── BRAND-CONSTITUTION.md              # LIVE · GRACE·GRIT·GLORY
├── GOVERNANCE.md                      # LIVE
├── CONTRIBUTING.md                    # LIVE
├── SECURITY.md                        # LIVE
├── LICENSE                            # LIVE
├── EVIDENCE-AND-PROVENANCE-METHOD.md  # LIVE
├── EVIDENCE-AND-EDITORIAL-STANDARDS.md # LIVE
├── docs/
│   ├── README.md                      # LIVE
│   ├── portfolio-decision-2026-10-31.md # LIVE · current portfolio and launch direction
│   ├── before-africa-research-dossier-2026-11-07.md  # LIVE · expanded 2026-11-11
│   ├── glossary.md                    # LIVE (updated 2026-11-11)
│   ├── public-presence.md             # LIVE
│   ├── decision-provenance.md         # LIVE
│   ├── succession.md                  # LIVE
│   ├── ai-automation-architecture.md  # LIVE
│   ├── MASTER-TOPIC-REGISTER.md       # LIVE · programme topic index
│   ├── research-briefs/
│   │   ├── continental-atlas-and-populations-2026-11.md  # LIVE
│   │   ├── nakebusen-name-exploration-2026-11.md         # LIVE · architecture approved 2026-11-11
│   │   └── …
│   └── releases/                      # PLANNED
├── research/                          # LIVE scaffold
│   ├── README.md
│   ├── bibliography/                  # master bibliography v0.1
│   ├── source-inventory/              # internal targets (empty rows OK)
│   └── claims/
└── skills/                            # LIVE skill packs

donfelohke.github.io/                  # PUBLIC SITE
├── index.html                         # LIVE · English-first audience hierarchy
├── docs/                              # WEBCOPY, design standards, SERVICE-CATALOG, …
└── tests/

NAKEBUSEN/ · WARENA/ · Gallery/ · Genje/ · Ikai/
└── domain READMEs and specialist docs
```

---

## 3. Domain ownership (who owns which facts)

| Fact domain | Canonical location | Status |
|-------------|-------------------|--------|
| Brand pillars GRACE·GRIT·GLORY | `BRAND-CONSTITUTION.md` | LIVE |
| ONLY NAKEBUSEN TRANSACTS | Brand constitution + public copy | LIVE |
| Loc campaign starting prices 700+ / 1,500+ / 3,500+ | NAKEBUSEN service catalogue + current campaign record | APPROVED FOR ELDORET CAMPAIGN; final quote remains scope-dependent |
| Location phrase Eldoret Town / Karibu Mdosi | Website + service catalogue | LIVE |
| Programme topics | `docs/MASTER-TOPIC-REGISTER.md` | LIVE |
| Evidence labels | `EVIDENCE-AND-EDITORIAL-STANDARDS.md` | LIVE |
| Public handles / sameAs | `docs/public-presence.md` | LIVE |
| Website design (no graphics) | site WEB-DESIGN-STANDARDS | LIVE |
| Public language policy (English default; Kiswahili toggle) | Website WEBCOPY + PR #33 | PARTIAL |
| Gallery asset approval | Gallery/ASSET-MANIFEST.md + ASSET-APPROVAL-WORKFLOW.md | INITIAL INVENTORY DOCUMENTED |
| WARENA stack / RDE | WARENA docs | PARTIAL |
| IKAI maturity | Always WIP / research | LIVE rule |
| Before Africa research programme | `docs/before-africa-research-dossier-2026-11-07.md` + research-briefs | LIVE (research maturity) |
| NAKEBUSEN name exploration | `docs/research-briefs/nakebusen-name-exploration-2026-11.md` | LIVE · architecture approved 2026-11-11 |

---

## 4. Master topic → documentation file

| — | Current portfolio and GENJE launch direction | **docs/portfolio-decision-2026-10-31.md** |
| — | Before Africa (naming, populations, knowledge, heritage) | **docs/before-africa-research-dossier-2026-11-07.md** |
| — | Continental atlas & populations brief | **docs/research-briefs/continental-atlas-and-populations-2026-11.md** |
| — | NAKEBUSEN name exploration | **docs/research-briefs/nakebusen-name-exploration-2026-11.md** (architecture approved 2026-11-11) |

| # | Topic | Primary docs |
|---|--------|--------------|
| 01–27 | Full programme inventory | **docs/MASTER-TOPIC-REGISTER.md** |
| — | Documentation tree | **This file** |
| — | Bibliography / claims | **research/** |
| — | Website | donfelohke.github.io docs + index.html |
| — | Brand | BRAND-CONSTITUTION · glossary |
| — | AI | docs/ai-automation-architecture.md |

Cross-repo research notes:
- Genje: `docs/BEFORE-AFRICA-LIVITY-AND-EMBODIED-KNOWLEDGE-2026-11-07.md`
- Ikai: `docs/BEFORE-AFRICA-EXISTENCE-AND-KNOWLEDGE-2026-11-07.md`
- NAKEBUSEN: `docs/NAKEBUSEN-NAME-NOTE.md` (pointer to corpus brief)

---

## 5. Content management workflow

1. Shared facts (price, brand, transaction boundary) → corpus or NAKEBUSEN catalogue first.  
2. Public page behaviour → donfelohke.github.io; CI + browser gates.  
3. Visual assets → Gallery only.  
4. Research claims → editorial evidence labels.  
5. Translation → both languages; human Kiswahili review before release.

---

## 6. Implementation status snapshot (updated 11 Nov 2026)

| Deliverable | Status |
|-------------|--------|
| Documentation tree | **LIVE** |
| Master Topic Register | **LIVE** |
| Evidence editorial standards | **LIVE** |
| Research bibliography v0.1 | **LIVE** scaffold |
| Before Africa master dossier | **LIVE** (expanded 2026-11-11) |
| Continental atlas & populations brief | **LIVE** |
| NAKEBUSEN name exploration brief | **LIVE · architecture approved 2026-11-11** |
| Website audience hierarchy (EN) | Pages workflow succeeded for main; live browser rendering not independently re-checked in this update |
| English default + Kiswahili toggle | PR status as previously recorded |
| Gallery approved assets | No assets inventoried or approved in `Gallery/ASSET-MANIFEST.md` |
| Cultural research index (deep) | Advanced via Before Africa dossier |

**Governing rule:** one source of truth per fact · clear links · preserved originals · reviewable changes · no implementation claim without evidence.

**Name exploration standing rules (approved 11 Nov 2026):**
- Turkana-rooted cultural association, community-reported meaning, unverified etymology.
- Founder’s aesthetic interpretation of the name is not linguistic or morphological evidence.
- Next recommended milestone: primary-source or community-verified Turkana pronunciation and lexical analysis with speaker attribution and permission.

## 7. Desktop-stack research ownership — 2026-11

| Topic | Canonical location | Boundary |
|---|---|---|
| Desktop stack, package managers, compositor and shell evaluation | [WARENA desktop-stack decision](https://github.com/donfelohke/WARENA/blob/main/docs/desktop-stack-decision-2026-11.md) | WARENA technical owner; RESEARCH only until hardware verification |
| Cross-project implications | [Desktop-stack alignment](docs/desktop-stack-alignment-2026-11.md) | Corpus owns cross-domain boundaries; no project inherits deployment claims |

The current evaluation is GNU Guix + RDE foundation; Niri + Noctalia v5 practical candidate; Sway fallback/comparator; dwl-guile experimental; Nix/NixOS comparator. NAKEBUSEN DIGITAL may make compatibility claims only after documented service testing. IKAI and GENJE may consume validated infrastructure but do not own the desktop platform. Gallery's asset workflow remains independent.
