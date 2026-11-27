# GitHub Account Revamp — Manual Settings and Copy

**Updated:** 27 November 2026 · original guide 24 November 2026  
**Programme:** [Coordinated revamp issue #78](https://github.com/donfelohke/feloh-corpus/issues/78)  
**Status:** Copy and order proposal for manual GitHub account settings  
**Authority:** Founder-approved identity and repository architecture

The connected GitHub integration can update repository files and create pull requests, but it does not expose the account profile editor, pinned repository reorder, repository description editor or topic editor. Apply the following settings manually in GitHub.

## 0. Current metadata audit — 26 November 2026

Authenticated GitHub API recheck on 27 November 2026 confirmed the following across all ten existing public repositories:

- **7/10 repositories have no description.**
- **3/10 have descriptions:** `donfelohke`, `dwl-guile` and `home-service-dwl-guile`.
- **10/10 have no repository topics.**
- **10/10 have no homepage URL set** in repository metadata.
- All ten are public, unarchived and use `main` as their default branch.

The connected GitHub integration can update repository files but does not expose repository description, homepage URL, topic, profile or pin writes. The copy-ready descriptions and topics below therefore remain manual account actions; no metadata change is claimed as applied. Set a repository homepage URL only when that repository has a real, maintained public destination; do not fill the field with the umbrella website merely to remove an empty value.

**Current pillar mapping:** GRACE → NAKEBUSEN; GRIT → WARENA; GLORY → GENJE / GENJENESS. GENJE's authored English interpretation is GREATNESS; WARENA's authored English interpretation is THE POWERFUL. These are distinct authored brand interpretations, not interchangeable synonyms or literal dictionary translations. FELOH remains the human author and decision-maker. IKAI remains MIRROR / reflective-computing research. **ONLY NAKEBUSEN TRANSACTS.**

See the [current identity clarification](IDENTITY-CANONICAL-CLARIFICATION-2026-11-26.md) for the shared source of record.

## 1. Profile presentation

**Display name:** Felix Lwova · Don Feloh

**Bio (copy-ready):**
```text
Founder · CTO · Loctician · Creative Technologist | Kenya
```

**Website:**
```text
https://donfelohke.github.io/
```

**Location:** Eldoret, Kenya

**Social link:** X — https://x.com/donfelohke

Use the profile README as the detailed introduction. Do not duplicate the entire brand constitution in the short bio.

## 2. Pinned repositories — exact order

Pin these six repositories in this order:

1. `donfelohke.github.io` — public website and primary entry point
2. `NAKEBUSEN` — primary enterprise and only transaction interface
3. `WARENA` — systems engineering and infrastructure
4. `feloh-corpus` — shared canon, evidence and provenance
5. `Ikai` — reflective-computing research
6. `Genje` — creative and embodied practice

Keep `Gallery`, `dwl-guile` and `home-service-dwl-guile` discoverable in the repository list, but do not let supporting infrastructure displace the six primary public destinations.

## 3. Repository descriptions

Use concise descriptions that explain the actual project without claiming unverified release status.

| Repository | Suggested description |
|---|---|
| `donfelohke.github.io` | Public home for Don Feloh: NAKEBUSEN enterprise, WARENA systems engineering, IKAI research, GENJE creative practice and FELOH Corpus |
| `NAKEBUSEN` | Natural loc care and practical technical services in Eldoret, Kenya — the primary enterprise and sole transaction interface |
| `WARENA` | Libre-first, local-first systems engineering, GNU/Linux, infrastructure and reproducible computing |
| `feloh-corpus` | Shared canon, research governance, evidence, provenance and cross-project indexes |
| `Ikai` | Reflective-computing, mirror-systems and human-directed interaction research — work in progress |
| `Genje` | Genge-rooted sound, livecoding, movement, choreography and embodied creative practice |
| `Gallery` | Asset provenance, rights, consent and approval records for the FELOH ecosystem |
| `donfelohke` | GitHub profile and project index for Felix Lwova · Don Feloh |
| `dwl-guile` | Guile-configurable dwl Wayland compositor with REPL — supporting WARENA engineering project |
| `home-service-dwl-guile` | GNU Guix Home service for dwl-guile configuration in Guile Scheme |

## 4. Suggested repository topics

Topics are discovery metadata, not proof of implementation or release. Add only the topics that accurately match the repository's current contents. The website topics below describe its static, bilingual public-home implementation; they do not imply a web-application runtime.

| Repository | Suggested topics |
|---|---|
| `donfelohke.github.io` | `github-pages`, `static-site`, `html`, `css`, `accessibility`, `bilingual`, `portfolio` |
| `NAKEBUSEN` | `loc-care`, `eldoret`, `kenya`, `beauty-services`, `natural-hair-care`, `small-business` |
| `WARENA` | `gnu-linux`, `guile`, `scheme`, `reproducible-builds`, `infrastructure`, `local-first`, `libre-software` |
| `feloh-corpus` | `research-governance`, `provenance`, `documentation`, `knowledge-management`, `evidence` |
| `Ikai` | `reflective-computing`, `human-computer-interaction`, `optics`, `mirror-systems`, `privacy`, `research` |
| `Genje` | `livecoding`, `genge`, `algorithmic-music`, `choreography`, `movement-notation`, `creative-coding` |
| `Gallery` | `asset-provenance`, `rights-management`, `consent`, `approval-workflow`, `creative-assets` |
| `donfelohke` | `profile-readme`, `portfolio`, `personal-website` |
| `dwl-guile` | `wayland`, `dwl`, `guile`, `scheme`, `linux`, `compositor` |
| `home-service-dwl-guile` | `guix`, `guix-home`, `guile`, `scheme`, `wayland`, `dwl` |

## 5. Manual application steps

1. Open https://github.com/settings/profile.
2. Set the display name, bio, location, website and social link using the values above.
3. Open https://github.com/donfelohke.
4. In the pinned repositories section, select **Customize your pins**.
5. Pin the six repositories in the exact order above and save.
6. Open each repository's **About** section, edit its description and topics, then save.
7. Revisit the profile page in a signed-out/private browser window and confirm the public first impression and pinned order.

## 6. Copy and governance rules

- The profile is the human-author landing page; the website is the primary public home.
- NAKEBUSEN leads commercially. **ONLY NAKEBUSEN TRANSACTS.**
- WARENA is capability, IKAI is research, GENJE is creative practice and FELOH Corpus is governance/provenance.
- Do not call IKAI a released product, GENJE a WARENA subsidiary or Gallery a live public gallery.
- Do not imply every repository is a finished product.
- Keep profile copy concise; send technical detail to the specialist README and Corpus.


## 7. Recheck record — 27 November 2026

The authenticated GitHub API was queried again for all ten repositories. The result remains:

- **7 repositories without descriptions**; only the profile README repository and the two supporting Guile repositories have descriptions.
- **10 repositories without topics**.
- **10 repositories without a homepage URL** (null or empty).
- The six-repository pin order above remains the intended public discovery order.

The API recheck does not prove that profile display name, bio, location, website, X link or pins have been changed. Verify those manually after application, using a signed-out browser session. Do not report the account presentation as complete until that check is recorded.

## 8. Fields not changed or not independently verified — 27 November 2026

The authenticated GitHub connector confirmed the account login as `donfelohke`, the current connected display name as `F3L0H #HisGenjeness`, and the current avatar resource URL. It does not expose the account profile editor or a reliable public rendering of every manual profile field.

Treat the following carefully:

- **Display name:** current connected value is `F3L0H #HisGenjeness`; proposed public display name remains `Felix Lwova · Don Feloh` as specified above.
- **Bio, company, location, website, social links, pronouns and status:** not independently read back from the public profile in this pass. Apply only the approved copy in this guide; do not report completion before a signed-out verification.
- **Company:** no new company value is prescribed here. Do not imply WARENA is the parent company of NAKEBUSEN or the other practices.
- **Pronouns:** no value was supplied for this audit. Leave unchanged rather than infer.
- **Status message:** no new status text was approved. Leave unchanged rather than inventing an availability or hiring claim.
- **Avatar:** the account avatar resource was retrieved, but its visual quality, identity suitability and crop were not independently reviewed. Do not replace it without a separate visual review and explicit selection.
- **Public email:** an email value returned by an authenticated connector is not evidence that the address is publicly visible. Do not copy it into the public profile or expose it as a contact route without explicit confirmation.

## 9. Completion record

| Area | State |
|---|---|
| Public website and README alignment | MERGED |
| Specialist README and research documentation updates | MERGED |
| Profile README | MERGED |
| Account display name / bio / location / website / social fields | MANUAL APPLICATION PENDING |
| Six pinned repositories | MANUAL APPLICATION PENDING |
| Repository descriptions and topics | MANUAL APPLICATION PENDING |
| Company / pronouns / status / avatar | NOT CHANGED; owner decision or visual review required |
| Signed-out public profile verification | PENDING |

Do not mark the account revamp complete until the manual fields, pins and repository About metadata are applied and the public profile is checked while signed out.


## 10. Profile README refresh — 27 November 2026

The profile README at [donfelohke/README.md](https://github.com/donfelohke/donfelohke/blob/main/README.md) was refreshed directly on the default branch after the latest account and research audit.

**Commit:** [9391e5104d191d692fbcee99b8c1bde3a5868daa](https://github.com/donfelohke/donfelohke/commit/9391e5104d191d692fbcee99b8c1bde3a5868daa)

The update:
- preserves the founder-approved six-repository discovery and pin order;
- records WARENA's current recursive expansion, **Warena Architecture Re Network/ed Artefact**, and distinguishes it from the authored English interpretation **THE POWERFUL**;
- adds the 27 November cross-domain synthesis on cooperative/federated computing and embodied interaction;
- adds the current GENJE livecoding research record;
- adds the FSF machine-learning freedom announcement as an external research lead, not as a claim of completed evaluation or implementation;
- identifies Utility Shell Kernel as exploratory architecture discussion, not an implemented kernel;
- retains research/implementation/deployment evidence boundaries and **ONLY NAKEBUSEN TRANSACTS**.

**Verification:** the updated README was fetched again from the default branch. The canonical expansion, research links, Utility Shell Kernel maturity boundary and six-repository order were confirmed in the returned content.

This file update does not change account-level profile fields, repository About metadata, topics or pinned repositories. Those remain manual actions described above.
