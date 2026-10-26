# Cross-Domain Learning Paths

**Status: PROPOSED CURRICULUM MAP.** These are study sequences, not completed training, certification claims, or proof of competence. Choose a concrete output for each stage and record the work, sources, and test evidence.

## How to use the paths

1. Choose a real question or small project.
2. Check prerequisites and select one primary source or course.
3. Study a bounded section; take notes in your own words with citations.
4. Build or analyse a small artefact.
5. Test it, record the result, and identify what remains unknown.
6. Ask for review or reproduce the work from a clean starting point.
7. Update the learning record only when the activity is actually complete.

## Path A — Computer science foundations

**Audience:** learner building a durable computer-science base.

1. Use [Teach Yourself Computer Science](https://teachyourselfcs.com/) as a subject map; inspect its current recommended resources.
2. Study programming and data structures; implement small exercises rather than only reading.
3. Study algorithms and complexity; compare expected complexity with measured behaviour.
4. Study computer architecture and operating systems; inspect process, memory, filesystem, and I/O behaviour.
5. Study networking and databases; build a local client/server or database exercise.
6. Study languages/compilers and distributed systems when the prerequisites are in place.
7. Publish a small project with source, dependencies, test steps, and a limitations note.

**Evidence of progress:** completed exercises, source commits, reproducible instructions, tests, and an explanation of trade-offs. Course browsing alone is not completion.

## Path B — GNU/Linux, Guix, and reproducible environments

**Audience:** systems operator or developer.

1. Establish a host inventory: hardware, architecture, firmware, OS, storage, and recovery constraints.
2. Learn shell fundamentals, processes, permissions, logs, filesystems, package management, and service supervision on a recoverable test environment.
3. Use the [GNU Guix manual](https://guix.gnu.org/manual/) for the installed version; record the Guix revision and channel inputs.
4. Define a small development environment and pin source/configuration inputs where supported.
5. Evaluate/build in isolation; preserve exact commands, exit status, output and environment details.
6. Repeat from a clean environment and compare the specified artefacts.
7. Test rollback and restoration separately before production use.

**Evidence of progress:** host record, pinned inputs, build logs, artefact comparison, second-run record, and recovery evidence. A declarative file or successful single build is not proof of reproducibility.

## Path C — Secure web delivery and GitHub Pages

**Audience:** site maintainer.

1. Define audiences, primary task, content truth, and conversion action.
2. Build a semantic, mobile-first page with clear headings, visible focus, usable forms/links, and no unnecessary external dependencies.
3. Use [WCAG 2.2](https://www.w3.org/TR/WCAG22/) as a testable reference; select the intended conformance level.
4. Use [NIST SSDF](https://csrc.nist.gov/pubs/sp/800/218/final) to organise secure-development questions and a pinned [OWASP ASVS](https://asvs.owasp.org/) release to derive relevant application checks.
5. Test at narrow viewport widths, keyboard-only, with zoom, and on an actual mobile device where available.
6. Check broken internal links, page metadata, theme persistence (if implemented), browser console errors, and the actual deployed URL.
7. Keep a record of the commit, workflow result, deployment status, and observed live behaviour.

**Evidence of progress:** test matrix with expected/observed results and environment. CI passing alone does not prove the deployed page is correct or accessible.

## Path D — Evidence-first research and documentation

**Audience:** researcher, writer, or knowledge-base maintainer.

1. State one research question, intended use, scope, exclusions, and date range.
2. Search the existing corpus before creating another document.
3. Find primary sources first where appropriate; record author/institution, version/date, URL, and access date.
4. Extract claims into a claim/source matrix with exact passage, table, page, commit, or observation.
5. Search for counter-evidence and determine whether corroborating sources are independent.
6. Separate source statement, observed fact, inference, opinion, testimony, hypothesis, and proposal.
7. Record uncertainty, source limitations, rights, consent, and privacy constraints.
8. Write a bounded conclusion and list what evidence would change it.

**Evidence of progress:** an annotated bibliography, claim records, explicit limitations, and a reproducible retrieval trail. A list of URLs is not an evidence synthesis.

## Path E — Kenya market and informal-economy research

**Audience:** business planner or service designer.

1. Define the product/service, customer segment, geography, and decision the research must support.
2. Use [KNBS Economic Survey 2026](https://www.knbs.or.ke/reports/2026-economic-survey/) for national context; cite exact table, period, units, and definitions.
3. Locate county-level, sector-specific, and current customer evidence where available.
4. Distinguish TAM, SAM, and SOM and state assumptions; do not infer a local addressable market from national GDP or sector growth alone.
5. Compare competitor offers using date-stamped, publicly accessible sources; distinguish advertised price from confirmed final quote.
6. Interview or survey only with a clear purpose and appropriate consent; avoid collecting unnecessary personal data.
7. Record uncertainty, sampling bias, seasonality, and next validation step.

**Evidence of progress:** sourced market table, transparent calculations, local assumptions, and a validation plan. No market size is asserted by this pathway itself.

## Path F — NAKEBUSEN LOCS and DIGITAL service quality

**Audience:** owner/operator or contributor.

1. Separate owner-approved service facts from draft copy, proposed services, and competitor comparisons.
2. Confirm service scope, inclusions/exclusions, starting price, factors affecting price, location, and current availability before publication.
3. Make the enquiry process clear: an enquiry is not a confirmed appointment or accepted job.
4. For digital work, document problem, constraints, deliverables, risks, tests, rollback, and handover before execution.
5. Use private, appropriately controlled systems for customer records; do not put personal records or payment references in public Git.
6. Review feedback and incidents without inventing testimonials or promising outcomes unsupported by evidence.

**Evidence of progress:** dated owner approval, versioned service catalogue, completed service/test record, and handover or aftercare note as relevant.

## Path G — IKAI reflective-compute research

**Audience:** researcher/prototyper.

1. Start with the [IKAI research agenda](https://github.com/donfelohke/Ikai/blob/main/docs/research-agenda.md) and privacy model.
2. Define a research question and a falsifiable or assessable success/failure criterion.
3. Use synthetic data or a local isolated environment where possible.
4. Map data sources, processing, retention, access, export and deletion before collecting participant data.
5. Do not infer health, emotion, identity, personality, or capability from movement/sensor data; do not score, diagnose, identify, or covertly profile people.
6. Record implementation, observation, interpretation, alternative explanations, and limitations separately.
7. Test participant control and deletion behaviour before making claims about privacy or safety.

**Evidence of progress:** reviewed protocol, data-flow diagram, test record, consent/privacy review where relevant, and limitations. A policy statement is not an implementation audit.

## Path H — GENJE livecoding, performance, and choreohacking

**Audience:** creative technologist or performer.

1. Record the creative question, cultural context, authorship, collaborators, and intended audience.
2. Identify the runtime, source commit, hardware, software versions, audio/visual routing, and external media.
3. Verify licences and permissions for samples, code, images, video, recordings, and participant contributions.
4. Capture a minimal reproduction procedure while distinguishing repeatable composition from live improvisation.
5. Test the setup in the target environment; record differences and limitations.
6. Respect consent, accessibility, and distribution limits for workshops and recordings.
7. Archive source and credits with a durable work record.

**Evidence of progress:** source/asset provenance, credits, performance record, reproduction notes, and test observations. A recording alone does not prove that a performance can be reproduced.

## Learning record template

For each learning unit, record:

- Path / unit:
- Question or learning objective:
- Source and exact version:
- Date started / reviewed:
- Notes and key claims:
- Exercise or artefact:
- Repository and commit:
- Tests / observed results:
- What remains uncertain:
- Next step:
- Status: `QUEUED` / `IN PROGRESS` / `PRACTISED` / `REVIEWED` / `REVISIT`

Do not mark a path complete merely because its resources have been collected.
