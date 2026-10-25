# Security Policy

## Scope

This repository is primarily a documentary corpus. Security reports may concern accidental disclosure, unsafe examples, compromised repository workflows, or security-sensitive implementation material documented here.

## Reporting a concern

Please do not publish credentials, exploit details, private data, or a live vulnerability in a public issue. Use GitHub's private vulnerability reporting feature if it is enabled for this repository. If it is unavailable, contact the repository maintainer through a verified private channel listed on the owner's GitHub profile.

Do not assume that a private reporting feature or a response-time commitment is configured unless GitHub shows it as enabled.

## Please include

- A concise description of the issue and its potential impact.
- The affected file, commit, workflow, or component.
- Reproduction details that can be shared safely.
- Any suggested mitigation.

## Handling principles

- Minimize exposure of secrets and personal data.
- Do not test against systems or accounts without authorization.
- Coordinate public disclosure after a fix or mitigation where feasible.
- If a secret is committed, revoke or rotate it first; deleting the visible file alone does not invalidate the secret or remove it from Git history.

## Current status

- Security policy: **LIVE — documentation**
- Automated scanning, private vulnerability reporting, branch protections, and incident-response automation: **UNKNOWN until separately verified**
