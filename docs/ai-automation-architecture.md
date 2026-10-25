# GitHub AI and Automation Architecture

**Status:** RESEARCH / RECOMMENDATION  
**Review date:** 2026-10-25  
**Scope:** All eight public FELOH ecosystem repositories  
**Decision state:** Proposed; no platform-wide automation or permissions are asserted to be configured by this document.

## 1. Purpose

Define a safe, reviewable path from AI-assisted research to changes in the FELOH GitHub ecosystem. The architecture must preserve human authorship, repository boundaries, evidence provenance, least privilege, privacy, and the distinction between documented intent and verified execution.

**Governing principles:** ONE CORPUS → MANY VIEWS → ONE PRACTICE. ONLY NAKEBUSEN TRANSACTS.

This document is a research record and recommendation. It does not itself install an application, grant permissions, enable a GitHub feature, or prove that any automation is active.

## 2. Repository map and observed baseline

The connected GitHub repository listing returned these eight public repositories, each with `main` as its default branch and `archived: false` at the time of inspection:

| Repository | Responsibility | Observed automation baseline |
|---|---|---|
| [feloh-corpus](https://github.com/donfelohke/feloh-corpus) | Canonical definitions, governance, evidence, decisions and shared research | No workflow runs returned; the repository contains the proposed custom-skill pack; PR [#5](https://github.com/donfelohke/feloh-corpus/pull/5) is open for the Sun Burn archive scaffold |
| [WARENA](https://github.com/donfelohke/WARENA) | Systems, reproducibility, infrastructure and recovery | `validate.yml`; latest inspected main-branch run succeeded |
| [Genje](https://github.com/donfelohke/Genje) | Creative technology, performance and embodied practice | `validate.yml`; latest inspected main-branch run succeeded |
| [Ikai](https://github.com/donfelohke/Ikai) | Reflective-compute research and privacy boundaries | `validate.yml`; latest inspected main-branch run succeeded |
| [NAKEBUSEN](https://github.com/donfelohke/NAKEBUSEN) | Beauty craft, approved public information and business operations | `validate.yml`; latest inspected main-branch run succeeded |
| [donfelohke.github.io](https://github.com/donfelohke/donfelohke.github.io) | Public website | Current `main` source at the latest inspected base includes Open Graph description, text-only theme control and Organization JSON-LD. Current main workflow outcome was not retrieved in this refresh. PR [#27](https://github.com/donfelohke/donfelohke.github.io/pull/27) proposes Kiswahili-first copy, language controls, stronger tests and SHA-pinned actions; its latest inspected static workflow passed. PRs #23–#25 report non-mergeable and need reconciliation. |
| [Gallery](https://github.com/donfelohke/Gallery) | Curated assets, provenance, rights and approvals | Main has no workflow runs; PR [#4](https://github.com/donfelohke/Gallery/pull/4) adds agent guidance and governance CI, and its first PR check passed |
| [donfelohke](https://github.com/donfelohke/donfelohke) | GitHub profile presentation | No workflow runs returned; recursive tree contains only `README.md` and no repository-local workflow or `AGENTS.md` |

Run results are point-in-time observations, not full historical or security audits. An empty Actions run listing does not establish that Actions is disabled. Repository contents and settings must be rechecked before implementation.

## 3. Recommended automation model

Use four explicit levels. Every repository and workflow should state which level it implements.

1. **Observe:** read repositories, issues, pull requests, commits, workflow results and approved public sources. Produce citations, inventories and uncertainty notes. No writes.
2. **Recommend:** draft analysis, issue descriptions, change plans and test plans. A human decides whether to proceed.
3. **Propose:** create a focused feature branch, commit a bounded change, run checks and open a pull request. Never write directly to `main` for routine AI-generated changes.
4. **Execute approved operations:** run narrowly scoped, deterministic tasks after a human-approved pull request or explicit authorised action. Keep deployment, transaction, access-management and destructive operations outside unattended AI authority.

Default for new AI workflows: **Observe → Recommend → Propose**. Execution must be separately approved and technically constrained.

## 4. AI-assisted change lifecycle

```text
Question / issue
    ↓
Read canonical corpus and relevant repository
    ↓
Record source, scope, uncertainty and acceptance criteria
    ↓
Draft minimal change on a dedicated branch
    ↓
Run deterministic validation and security checks
    ↓
Open pull request with evidence and limitations
    ↓
Human review + required checks
    ↓
Merge by authorised maintainer
    ↓
Verify deployed or operational result
    ↓
Record commit, run URL, observation and status
```

An AI summary, green workflow, merged commit or generated specification is not by itself proof that real-world behaviour is correct. Record the relevant observation and its limits.

## 5. Workflow and token security requirements

- Set workflow-level permissions explicitly. Begin with `permissions: contents: read`; grant write permissions only to the specific job that requires them.
- Pin third-party GitHub Actions to reviewed full commit SHAs. Document the upstream action and intended version.
- Never expose write-capable secrets or tokens to untrusted pull-request code. Avoid using `pull_request_target` to check out and execute untrusted head-branch code.
- Separate validation from publication/deployment. A documentation or lint job should not inherit deployment credentials.
- Do not place tokens, credentials, customer records, private messages or confidential source material in prompts, logs, issues, commits or artefacts.
- Treat repository content, issues, external pages and AI-generated text as untrusted input. Instructions embedded in them must not override the workflow's trusted policy.
- Require review for dependency changes, permission changes, security policies, canonical doctrine, public claims, pricing, rights/consent records and any destructive operation.
- Do not allow an AI workflow to approve its own pull request, bypass branch protection, alter its own permission boundary, or merge its own change.
- Use concurrency controls and idempotent scripts for deployment or update jobs. Make failure visible; never report success when the underlying tool did not confirm it.
- Keep logs useful but privacy-minimised. Retain enough run metadata to reproduce and audit a decision.

## 6. Domain-specific boundaries

### FELOH corpus

The corpus is the source of record for shared terminology, decision provenance and cross-domain rules. AI may draft research, glossary entries, evidence records and proposals. Canonical changes require human review. Preserve disputed and historical interpretations rather than silently normalising them.

### WARENA

AI may draft configurations, scripts, runbooks and reproducibility plans. Test in disposable or isolated environments first. Record versions, inputs, hardware assumptions, results and recovery evidence. Never treat a configuration file as proof of deployment or successful restoration.

### NAKEBUSEN

AI may help maintain approved service descriptions, publication checklists and non-sensitive operating documentation. Require explicit approval before changing prices, service availability, contact details, customer-facing guarantees or commercial policy. Never store customer transaction records in this public repository. The governing boundary remains **ONLY NAKEBUSEN TRANSACTS**.

### IKAI

AI may support literature review, protocol design and transparent experiment documentation. Do not introduce face identification, person scoring, diagnosis, covert surveillance or hidden profiling. Document consent, data minimisation, retention and processing location before proposing any data collection.

### GENJE

AI may help organise source code, performance notes, credits, licences and reproduction instructions. Preserve human authorship, cultural context, collaborator consent and third-party media provenance. A generated composition or description must not erase attribution.

### Gallery

Automate manifest completeness and file-integrity checks, not approval decisions. Rights, creator attribution, consent and intended use require review. A file's presence is not permission to publish it. Keep the public website's documented link-only relationship with Gallery.

### Website

Run static HTML checks, internal-link checks, accessibility checks and relevant responsive-browser tests before release. Keep deployment separate from untrusted pull-request validation. Verify the live site after a successful deployment.

### Profile repository

Validate links, Markdown and consistency with the canonical corpus. Avoid duplicating large bodies of doctrine; link to the authoritative records instead.

## 7. Shared validation tiers

Adopt checks incrementally, based on actual repository contents:

- **Tier 1 — Documentation:** required-file checks, Markdown lint, relative-link validation and status-label consistency.
- **Tier 2 — Web:** HTML validation, internal links, accessibility smoke tests, metadata checks and browser error checks.
- **Tier 3 — Software/configuration:** formatters, linters, unit tests, dependency review and reproducible build checks where relevant.
- **Tier 4 — Release/operations:** deployment verification, recovery tests, provenance records and release attestations where the project can support them.

A check must validate real requirements, not merely search for a phrase. Missing required files should fail with actionable diagnostics; update the requirements and workflow together through review.

## 8. Custom skills and AI agents

The corpus tree currently contains the conversation-derived skill pack under `skills/`, including the Sovereign Repository Steward and domain-specific skills. Its README marks the pack PROPOSED and asks for review before adoption. The existence of these files does not install them into GitHub Copilot, ChatGPT, or another agent; this document describes the wider operating architecture and does not duplicate the skills.

Recommended skill contract:

- State scope, authorised tools, inputs, outputs and prohibited actions.
- Prefer read-only inspection before proposing writes.
- Cite the source repository, file, commit, issue or workflow run for factual findings.
- Distinguish verified facts, inferences, recommendations and unknowns.
- Require explicit confirmation for material changes outside an already approved task.
- Never claim an action completed without a successful tool result.
- Produce reviewable, small diffs and explain tests, risks and rollback.
- Avoid hard-coded personal secrets, account-specific assumptions and hidden data collection.

Do not install unreviewed third-party agents or grant them repository-wide write access just because the app can be installed. Verify the publisher, code, permission scope, network behaviour, update policy and rollback path first.

## 9. Priority implementation plan

### P0 — Baseline and boundaries

1. Capture a dated inventory of all eight repositories, workflow files, recent runs, open pull requests and current branch/ruleset settings.
2. Review the existing custom-skills PR before designing overlapping automation.
3. Check the WARENA workflow's required paths against the current tree and latest run logs; keep the check meaningful and fix any real mismatch.
4. Verify the website's Pages source, recent deployment and public output.
5. Confirm that Gallery manifest entries and files are consistent without assuming rights approval.

### P1 — Safe proposal pipeline

1. Add a standard AI-assisted pull-request template documenting purpose, evidence, status impact, tests, privacy review and rollback.
2. Add or improve documentation checks in the corpus and Gallery, using minimal read-only workflow permissions.
3. Standardise branch naming and one-change-per-PR practice.
4. Require human review for canonical, security-sensitive, commercial and public-facing changes where repository controls support it.
5. Record run links and observed outcomes in the pull request.

### P2 — Cross-repository coordination

1. Maintain a canonical repository map and evidence register in the corpus.
2. Generate inventory reports from GitHub metadata rather than manually copying state.
3. Create separate PRs for domain-specific changes; do not use one broad token to mutate all repositories.
4. Add periodic read-only drift reports for broken links, missing documentation and outdated cross-references.
5. Establish backup, restoration and maintainer handover tests.

### P3 — Controlled execution

Only after P0–P2 are verified, consider narrowly scoped automation for routine metadata, release preparation, link maintenance or approved content synchronisation. Keep public releases, business transactions, access changes, destructive actions and merges behind explicit human-controlled gates.

## 10. Acceptance criteria

The architecture is not considered operational until there is evidence that:

- all eight repositories have a dated, reproducible inventory;
- each active workflow's purpose, triggers, token permissions and required checks are documented;
- AI-generated changes are submitted through reviewable branches and pull requests;
- relevant checks have successful run URLs on the proposed changes;
- branch protection or rulesets are configured and tested where required and supported;
- no AI agent can silently promote its own proposal to canonical policy or release;
- public assets and business claims have the required approval and provenance;
- release and recovery procedures have been exercised and recorded.

## 11.1 Targeted workflow permission review (2026-10-25)

A targeted read of the following workflow files was completed after the initial inventory:

| Repository / workflow | Observed permissions and trigger | Finding |
|---|---|---|
| `donfelohke.github.io/.github/workflows/html-check.yml` | Explicit `contents: read`; runs on `push` to `main` and `pull_request` | Read-only repository permission is appropriate for static checks. |
| `donfelohke.github.io/.github/workflows/pages.yml` | Explicit `contents: read`, `pages: write`, `id-token: write`; deploy workflow runs on pushes to `main` or manual dispatch; concurrency group `pages` | Deployment permissions are scoped to Pages publishing and OIDC. Keep this workflow separate from pull-request validation. |
| `WARENA/.github/workflows/validate.yml` | Explicit `contents: read`; pull-request and `main` push triggers; checkout action pinned to full commit SHA | Read-only baseline check; checkout is pinned to a commit. |
| `Genje/.github/workflows/validate.yml` | Explicit `contents: read`; pull-request and `main` push triggers; checkout action pinned to full commit SHA | Read-only baseline check; checkout is pinned to a commit. |
| `Ikai/.github/workflows/validate.yml` | Explicit `contents: read`; pull-request and `main` push triggers; checkout action pinned to full commit SHA | Read-only baseline check; checkout is pinned to a commit. |
| `NAKEBUSEN/.github/workflows/validate.yml` | Explicit `contents: read`; pull-request and `main` push triggers; checkout action pinned to full commit SHA | Read-only baseline check; checkout is pinned to a commit. |

**Follow-up findings and limits:**

- The current website `main` workflows use version tags (`actions/checkout@v7`, `actions/configure-pages@v6`, `actions/upload-pages-artifact@v5`, `actions/deploy-pages@v5`) rather than full commit-SHA pins. Website PR #27 now proposes reviewed full-SHA pins for both validation and Pages deployment. Those pins are on the PR branch only until reviewed and merged.
- The four documentation-validation workflows inspected use a full commit-SHA pin for `actions/checkout`.
- A targeted search did not find `pull_request_target` in those five repositories' indexed workflow files. This is not a complete proof that no such trigger exists in any workflow or branch.
- This inspection did **not** retrieve repository rulesets, branch protection, default workflow-token settings, secret access, app-installation permissions or environment protection rules. Those remain unknown.
- The review is limited to the named files and the inspected branch state; do not generalise these findings to the other three repositories or to all workflows.

## 12. Evidence limitations

This research observed repository metadata, selected file trees, workflow definitions, recent Actions runs and the open corpus custom-skills PR through the connected GitHub integration. It did not fully inspect every file, all workflow logs, app installation permissions, branch protection for every repository, secrets settings, dependency alerts, browser rendering, or recovery procedures.

Treat these as **UNKNOWN until independently verified**. Re-run the inventory before applying settings or granting new access. Do not infer that an empty workflow-run list means Actions is disabled, or that a successful documentation check proves application correctness.

## 13. Reference documentation

- [GitHub Actions workflow permissions](https://docs.github.com/en/actions/writing-workflows/workflow-syntax-for-github-actions#permissions)
- [Secure use of GitHub Actions](https://docs.github.com/en/actions/security-for-github-actions/security-guides/security-hardening-for-github-actions)
- [Managing a branch protection rule](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches)
- [GitHub rulesets](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-rulesets)
- [GitHub Copilot coding agent](https://docs.github.com/en/copilot/concepts/agents/coding-agent/about-coding-agent)

---
**Conclusion:** build a reviewable proposal pipeline before granting autonomous write authority. AI should increase research speed and reduce repetitive maintenance while preserving human authorship, least privilege, evidence quality and domain boundaries.


## 10. Follow-up evidence from the 2026-10-25 audit

This section records the results of the later read-only audit and must be refreshed when repository state changes.

- **Website main (historical snapshot):** commit `1c143206d4d27ab9719ffb561bb9e6fbb69b775c` had a failed `Static HTML checks` run while Pages deployment succeeded. That commit is no longer the latest inspected PR base; current `main` source was re-read and includes an Open Graph description, text-only theme control and Organization JSON-LD. A current main-branch run result was not retrieved in this refresh, so do not repeat the old failure as current status.
- **Website PR reconciliation:** PR [#23](https://github.com/donfelohke/donfelohke.github.io/pull/23) now reports non-mergeable against current `main`; do not merge it unchanged. Its useful theme/action-pin ideas were carried into PR [#27](https://github.com/donfelohke/donfelohke.github.io/pull/27). PRs [#24](https://github.com/donfelohke/donfelohke.github.io/pull/24) and [#25](https://github.com/donfelohke/donfelohke.github.io/pull/25) also report non-mergeable and overlap in copy, location, metadata and policy tests. PR #27 is the current integration candidate and is reported mergeable; its latest head `705299d72179ff6c49ec9153e79654f7c4e6a9ce` passed static validation at [run 40191667294](https://github.com/donfelohke/donfelohke.github.io/actions/runs/40191667294). That run covers static tests and simulated theme/language behaviour, not real-browser or viewport verification.
- **Website documentation and legacy PRs:** PR [#19](https://github.com/donfelohke/donfelohke.github.io/pull/19) has been refreshed to distinguish current main from proposed changes and remove the stale PR #17 reference. PRs #16 and #19 were based on older main ancestors; PRs #20–#22 and #24–#25 remain open and require current-base reconciliation. No old branch should be merged wholesale.
- **Gallery rights:** the repository contains a GPL-3.0 `LICENSE`, but the current README still says a repository-level code licence might be added later. PR [#2](https://github.com/donfelohke/Gallery/pull/2) corrects this wording and distinguishes repository code licensing from rights in individual curated assets. The manifest states that no assets have been inventoried or approved.
- **Gallery automation:** PR [#4](https://github.com/donfelohke/Gallery/pull/4) adds `AGENTS.md` and a read-only governance-baseline workflow. Its initial pull-request workflow check passed; the workflow is not yet on main.
- **Workflow security:** WARENA, Genje, Ikai and NAKEBUSEN have documentation-baseline workflows with `contents: read` and `actions/checkout` pinned to a full commit SHA. The Website workflows used version tags at the time of inspection; PR #23 proposes pinning the relevant actions. Gallery has no workflow on main until PR #4 is reviewed.
- **Agent guidance rollout:** documentation-only `AGENTS.md` proposals are open in [WARENA #3](https://github.com/donfelohke/WARENA/pull/3), [Genje #3](https://github.com/donfelohke/Genje/pull/3), [Ikai #3](https://github.com/donfelohke/Ikai/pull/3), [NAKEBUSEN #3](https://github.com/donfelohke/NAKEBUSEN/pull/3), [Corpus #8](https://github.com/donfelohke/feloh-corpus/pull/8), and [Profile #1](https://github.com/donfelohke/donfelohke/pull/1). The four repositories with existing validation workflows passed their checks; Corpus and Profile have no workflow runs, so their instruction-file proposals have no CI evidence.
- **Settings limitation:** attempts to read branch-protection endpoints returned HTTP 403 `Resource not accessible by integration` for all eight repositories. Branch protection, required reviews, and ruleset enforcement are therefore UNKNOWN from this audit; do not infer that protections are absent or enabled.
- **Browser limitation:** source and CI checks were inspected, but no successful live browser session or viewport screenshots were available. Responsive layout, real keyboard interaction, live WhatsApp handoff, and deployed theme behavior remain NOT VERIFIED.

## 14. Latest website and portfolio reconciliation — 2026-10-25

This section supersedes earlier website status statements above where the inspected branch or PR state has changed.

- **Website PR #27:** latest inspected head `705299d72179ff6c49ec9153e79654f7c4e6a9ce`; open and reported mergeable. Static workflow run [40191667294](https://github.com/donfelohke/donfelohke.github.io/actions/runs/40191667294) passed the HTML/content checks, inline JavaScript parser, and theme/language preference test. The test caught and led to correction of a language-handler syntax boundary and a test-harness mismatch during iteration. The final recorded run passed. No live-browser, screen-reader, viewport, or deployed-site verification was completed.
- **Website PR #23:** open but reported non-mergeable; preserve for reference and do not merge unchanged. The current PR #27 branch includes reviewed full-SHA pins for `actions/checkout`, `actions/configure-pages`, `actions/upload-pages-artifact`, and `actions/deploy-pages`; these pins are not on main until reviewed and merged.
- **Website PRs #24 and #25:** both open and reported non-mergeable. Their copy/metadata/policy changes overlap. Their PR bodies now document the need to port any unique approved improvements onto the current base rather than merge stale branches.
- **Website public copy correction:** PR #27 removes the unverified home-visit promise and instead states that appointment times and availability are confirmed directly. The approved starting prices remain KES 700, KES 1,500 and KES 3,500; the primary location phrase remains Eldoret Town / Karibu Mdosi. Kiswahili is the default proposed language; the copy still needs fluent Kenyan Kiswahili editorial review.
- **Website main status:** current main source inspected during this refresh contains an Open Graph description, a text-only theme control and Organization JSON-LD. A current main-branch workflow result was not retrieved. Do not describe the historical failure at `1c14320` as the current main state.
- **Gallery:** PR #4 remains the proposed governance workflow and agent contract; PR #2 addresses licence wording and asset rights; PR #5 addresses public copy and approval status. No asset was approved by these changes. Review the current heads and CI before any merge.
- **Other repository copy proposals:** [WARENA #4](https://github.com/donfelohke/WARENA/pull/4), [Genje #4](https://github.com/donfelohke/Genje/pull/4), [Ikai #4](https://github.com/donfelohke/Ikai/pull/4), [NAKEBUSEN #4](https://github.com/donfelohke/NAKEBUSEN/pull/4), [FELOH Corpus #10](https://github.com/donfelohke/feloh-corpus/pull/10), [Profile #2](https://github.com/donfelohke/donfelohke/pull/2) and [Gallery #5](https://github.com/donfelohke/Gallery/pull/5) were found open. The recorded PR-triggered validation runs for Genje #4, Ikai #4 and NAKEBUSEN #4 passed. No PR-triggered run was returned for WARENA #4, Corpus #10, Profile #2 or Gallery #5 in this inspection; this is not proof that no run exists. These are separate proposals and require repository-specific review; no portfolio-wide merge or production release was performed.
- **No merge/deployment:** no PR was merged and no production deployment was triggered by this audit. Branch protection/ruleset configuration remains unknown because the integration could not read those settings.