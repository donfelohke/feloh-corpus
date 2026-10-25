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
├── docs/
│   ├── README.md                      # LIVE · index of docs/
│   ├── glossary.md                    # LIVE
│   ├── public-presence.md             # LIVE · verified handles
│   ├── decision-provenance.md         # LIVE
│   ├── succession.md                  # LIVE
│   ├── ai-automation-architecture.md  # LIVE
│   ├── MASTER-TOPIC-REGISTER.md       # PLANNED · copy of scope register
│   ├── research/
│   │   ├── README.md                  # PLANNED
│   │   ├── source-inventory.md        # PLANNED
│   │   └── cultural-research-index.md # PLANNED · Black life / living memory
│   └── releases/
│       └── README.md                  # PLANNED · release notes index
└── skills/                            # LIVE skill packs
    ├── feloh-canon-keeper/
    ├── nakebusen-operator/
    ├── warena-systems-engineer/
    ├── ikai-researcher/
    ├── genje-choreohacker/
    └── sovereign-repository-steward/

donfelohke.github.io/                  # PUBLIC SITE
├── index.html                         # LIVE · English-first audience hierarchy
├── README.md                          # LIVE
├── docs/
│   ├── WEBCOPY.md                     # LIVE · master copy proposal
│   ├── WEB-DESIGN-STANDARDS.md        # LIVE
│   ├── SERVICE-CATALOG.md             # LIVE · must match prices
│   ├── AUDIENCE-MARKET-RESEARCH.md    # LIVE
│   ├── PR-RECONCILIATION-2026-10-25.md# LIVE
│   ├── ARCHITECTURE.md                # LIVE
│   ├── deployment.md                  # LIVE
│   ├── recovery.md                    # LIVE
│   ├── OPERATIONS.md                  # LIVE
│   ├── PRIVACY.md                     # LIVE
│   ├── brand-business-blueprint.md    # LIVE
│   └── …                              # other site ops docs
└── tests/                             # LIVE static checks

NAKEBUSEN/
├── README.md
└── docs/
    ├── service-catalogue.md           # LIVE · commerce baseline
    └── webcopy-research.md            # LIVE

WARENA/
├── README.md
└── docs/                              # PLANNED expansion · handbook, stack, recovery

Gallery/
├── README.md                          # LIVE · no empty claim of assets
├── CONTRIBUTING.md                    # LIVE if present
└── ASSET-MANIFEST.md                  # PLANNED until first approved asset

Genje/ · Ikai/
└── README.md + research notes         # LIVE minimal; maturity labels required
```

---

## 3. Domain ownership (who owns which facts)

| Fact domain | Canonical location | Status |
|-------------|-------------------|--------|
| Brand pillars GRACE·GRIT·GLORY | `feloh-corpus/BRAND-CONSTITUTION.md` | LIVE |
| ONLY NAKEBUSEN TRANSACTS | Brand constitution + all public copy | LIVE |
| Loc prices 700 / 1500 / 3500 | `NAKEBUSEN/docs/service-catalogue.md` + site SERVICE-CATALOG | LIVE · confirm before change |
| Location phrase Eldoret Town / Karibu Mdosi | Website + service catalogue | LIVE |
| Public handles / sameAs | `feloh-corpus/docs/public-presence.md` | LIVE |
| Website design rules (no graphics) | `donfelohke.github.io/docs/WEB-DESIGN-STANDARDS.md` | LIVE |
| Kiswahili-first policy | PR #27 + WEB-DESIGN-STANDARDS (when merged) | PARTIAL · not live on Pages |
| Gallery asset approval | `Gallery` manifest | PLANNED inventory |
| WARENA stack / RDE | `WARENA` docs | PARTIAL |
| IKAI maturity | Always WIP / research | LIVE rule |
| AI write limits | `docs/ai-automation-architecture.md` | LIVE |

---

## 4. Master topic → documentation file

| # | Topic | Primary docs |
|---|--------|--------------|
| 01 | GitHub governance | GOVERNANCE · CONTRIBUTING · website PR-RECONCILIATION · repository-plan |
| 02 | Website redesign | WEBCOPY · WEB-DESIGN-STANDARDS · ARCHITECTURE · deployment · index.html |
| 03 | Documentation tree | **This file** · docs/README.md |
| 04 | Webcopy EN/SW | WEBCOPY · service-catalogue · PR #27 (pending) |
| 05 | Cultural research / Black life | PLANNED `docs/research/cultural-research-index.md` · Corpus |
| 06 | Brand identity | BRAND-CONSTITUTION · glossary · brand-business-blueprint |
| 07 | Market / business | AUDIENCE-MARKET-RESEARCH · service-catalogue · blueprint |
| 08 | WARENA systems | WARENA README + handbook (expand) · skills/warena-systems-engineer |
| 09 | IKAI research | Ikai repo · skills/ikai-researcher · never product claims |
| 10 | Gallery archive | Gallery README · ASSET-MANIFEST (planned) |
| 11 | FELOH Corpus / Sun Burn | Corpus README · EVIDENCE method · research/ |
| 12 | AI workflows | ai-automation-architecture · SECURITY · skills/* |

---

## 5. Content management workflow

1. **Change a shared fact** (price, brand mapping, transaction boundary) → PR on **feloh-corpus** or **NAKEBUSEN** service catalogue first.  
2. **Change public page behaviour** → PR on **donfelohke.github.io**; CI + browser gates.  
3. **Add visual asset** → Gallery only; never embed on site.  
4. **Research claim** → evidence method labels: LIVE / PROTOTYPE / RESEARCH / CONCEPT / UNKNOWN.  
5. **Translation** → both languages in one PR when SW is active; human Kiswahili review before release.

---

## 6. Dependencies

```
BRAND-CONSTITUTION
    → WEBCOPY / service-catalogue / all README signatures

service-catalogue (prices)
    → index.html · WEBCOPY · ads · FB copy

WEB-DESIGN-STANDARDS
    → index.html · tests · CI

public-presence
    → schema sameAs · footers · profile README

PR-RECONCILIATION
    → merge order · no blind merge of stale homepage PRs

EVIDENCE-AND-PROVENANCE-METHOD
    → research docs · cultural materials · Gallery rights
```

---

## 7. Implementation status snapshot (25 Oct 2026)

| Deliverable | Status |
|-------------|--------|
| Documentation tree (this file) | **LIVE** |
| Brand constitution | LIVE |
| Audience research | LIVE (site docs) |
| Website audience hierarchy (EN) | LIVE on Pages |
| Kiswahili default + toggle | Open PR #27 · editorial pending |
| Gallery with approved assets | Repo LIVE · inventory empty |
| Full WARENA handbook | PARTIAL |
| Cultural research index | PLANNED |
| Profile README polish | Verify on GitHub UI |

---

## 8. Next fill-in order

1. Keep PR reconciliation discipline; Kiswahili editorial on #27.  
2. Align `SERVICE-CATALOG` / `service-catalogue` / live `index.html` after any price change.  
3. Write `docs/research/README.md` + source inventory when Corpus work resumes.  
4. Expand WARENA `docs/` with stack and recovery from existing handbooks.  
5. First Gallery asset only with manifest row (rights + consent).

**Governing rule:** one source of truth per fact · clear links · preserved originals · reviewable changes · no implementation claim without evidence.
