# FELOH / NAKEBUSEN — Complete documentation tree

**Status:** CANONICAL ARCHITECTURE · 25 October 2026  
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
│   ├── glossary.md                    # LIVE
│   ├── public-presence.md             # LIVE
│   ├── decision-provenance.md         # LIVE
│   ├── succession.md                  # LIVE
│   ├── ai-automation-architecture.md  # LIVE
│   ├── MASTER-TOPIC-REGISTER.md       # LIVE · programme topic index
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
| Public language policy (English default; Kiswahili toggle) | Website WEBCOPY + PR #33 | PARTIAL — PR #27 is closed/superseded; PR #33 remains open |
| Gallery asset approval | Gallery/ASSET-MANIFEST.md + ASSET-APPROVAL-WORKFLOW.md | INITIAL INVENTORY DOCUMENTED; no assets inventoried or approved |
| WARENA stack / RDE | WARENA docs | PARTIAL |
| IKAI maturity | Always WIP / research | LIVE rule |

---

## 4. Master topic → documentation file

| — | Current portfolio and GENJE launch direction | **docs/portfolio-decision-2026-10-31.md** |

| # | Topic | Primary docs |
|---|--------|--------------|
| 01–27 | Full programme inventory | **docs/MASTER-TOPIC-REGISTER.md** |
| — | Documentation tree | **This file** |
| — | Bibliography / claims | **research/** |
| — | Website | donfelohke.github.io docs + index.html |
| — | Brand | BRAND-CONSTITUTION · glossary |
| — | AI | docs/ai-automation-architecture.md |

---

## 5. Content management workflow

1. Shared facts (price, brand, transaction boundary) → corpus or NAKEBUSEN catalogue first.  
2. Public page behaviour → donfelohke.github.io; CI + browser gates.  
3. Visual assets → Gallery only.  
4. Research claims → editorial evidence labels.  
5. Translation → both languages; human Kiswahili review before release.

---

## 6. Implementation status snapshot (25 Oct 2026; portfolio decision addendum 31 Oct 2026)

| Deliverable | Status |
|-------------|--------|
| Documentation tree | **LIVE** |
| Master Topic Register | **LIVE** |
| Evidence editorial standards | **LIVE** |
| Research bibliography v0.1 | **LIVE** scaffold |
| Website audience hierarchy (EN) | Pages workflow succeeded for main commit `e0fc5f6631bb`; live browser rendering not independently checked in this audit |
| English default + Kiswahili toggle | PR #33 open; PR #37 is stacked on #33; PR #37 automated checks passed, but browser verification remains pending |
| Gallery approved assets | No assets inventoried or approved in `Gallery/ASSET-MANIFEST.md` |
| Cultural research index (deep) | PLANNED beyond register |

**Governing rule:** one source of truth per fact · clear links · preserved originals · reviewable changes · no implementation claim without evidence.
