---
title: "Waveframe Labs Website - Version Contract"
filetype: "documentation"
type: "version"
domain: "infrastructure"
version: "2.0.0"
status: "Active"
created: "2025-10-18"
updated: "2026-05-18"

author:
  name: "Waveframe Labs"
  url: "https://waveframelabs.org"

maintainer:
  name: "Waveframe Labs"
  url: "https://waveframelabs.org"

license: "CC-BY-NC-SA-4.0"

ai_assisted: "partial"

anchors:
  - "WF-WEBSITE-VERSION-v2.0.0"
---

# Version - WaveframeLabs.org

**Current Version:** `2.0.0`

## Version Semantics

Version `2.0.0` designates the second canonical public interface of the Waveframe Labs website.

This release materially changes the public interpretation of the site from an Aurora-first institutional overview into a product and protocol-facing execution-governance reference surface.

The v2.0.0 website centers:

- deterministic enforcement at the execution boundary
- the canonical governance-to-production architecture diagram
- installable runtime and developer infrastructure
- local Guard vs Cloud authority/audit responsibilities
- component boundary responsibilities
- compatibility and dependency specification
- concrete governed execution scenarios
- protocol evolution and release engineering notes

---

## v2.0.0 Canonical Architecture

The v2.0.0 architecture is:

```text
Human Governance
  -> Governance-Ledger
  -> Contract Compiler
  -> Compiled Authority Contract
  -> Proposal Normalizer
  -> Canonical Proposal
  -> CRI-CORE
  -> Execution Decision
  -> Waveframe Guard
  -> Production System
```

Waveframe Cloud provides:

- authority distribution
- audit durability
- registry
- receipts

Cloud does not decide admissibility.

---

## Scope of v2.0.0

Included in the v2.0.0 canonical interface:

- Product landing homepage aligned around execution-boundary enforcement
- Single reusable canonical architecture diagram asset
- Execution architecture map page
- Compatibility matrix and dependency specification page
- CRI-CORE kernel page focused on deterministic admissibility
- Tools page organized by governance, compilation, proposal, enforcement, and authority/audit layers
- Governed execution scenarios page
- Protocol evolution release log
- README aligned to v2.0.0 public architecture
- Site metadata and deployment logs aligned to this release

Out of scope for v2.0.0:

- Runtime implementation code
- Cloud service deployment
- Package publication
- Governance authority publication
- Dynamic documentation generation
- Analytics or telemetry

---

## Compatibility Profile

The v2.0.0 site documents compatibility profile:

`waveframe-execution-governance-2026-05`

The public compatibility surface includes:

- Governance-Ledger
- CRI-CORE Contract Compiler
- Proposal Normalizer
- CRI-CORE
- Waveframe Guard
- Waveframe Cloud v1 API semantics

The authoritative compatibility page is:

`compatibility.html`

---

## Versioning Policy

Website versions are incremented when:

- the public interpretation of the site materially changes
- canonical structure or authority relationships are altered
- new permanent reference surfaces are added
- the documented architecture changes compatibility expectations

Minor copy edits, visual adjustments, and routine content refreshes may not trigger a website version change.

---

Copyright 2026 Waveframe Labs.
