<p align="center">
  <img src="canonical-architecture.svg" alt="Waveframe canonical architecture diagram" width="760">
</p>

# Waveframe Labs - Website Repository

[![Waveframe Labs](https://img.shields.io/badge/WAVEFRAME%20LABS-Institutional%20Repository-FF6A00?style=flat)](https://waveframelabs.org)  
[![ORCID](https://img.shields.io/badge/ORCID-0009--0006--6043--9295-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0009-0006-6043-9295)  
![License: Apache-2.0](https://img.shields.io/badge/Code-Apache--2.0-blue)  
![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/Content-CC%20BY--NC--SA%204.0-lightgrey)

This repository hosts the canonical public website for **Waveframe Labs**.

The v2.0.0 website is the public interface for the Waveframe execution-governance architecture: deterministic authority publication, contract identity, canonical proposal assembly, CRI-CORE admissibility, Waveframe Guard runtime enforcement, and Waveframe Cloud authority/audit durability.

**Live site:** https://waveframelabs.org  
**Current website version:** `2.0.0`

---

## Canonical Architecture

The diagram above is the shared website and README asset for the v2.0.0 architecture:

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

Waveframe Cloud provides authority distribution, audit durability, registry, and receipts. It does not decide admissibility.

---

## Purpose and Scope

This repository exists to serve a single, well-defined role:

> To present the canonical, human-readable public representation of the Waveframe execution-governance architecture.

It is not a tooling repository, runtime implementation, governance authority, registry, or audit store. It points to authoritative artifacts and implementation repositories while maintaining a stable, auditable public reference surface.

This site is:

- Fully static
- Framework-free
- Buildless and deterministic
- Directly auditable from source

Every rendered page corresponds directly to a committed file in this repository.

---

## Authority Boundaries

This website:

- Does not define doctrine
- Does not author governance
- Does not compile contracts
- Does not normalize proposals
- Does not decide admissibility
- Does not enforce runtime execution
- Does not distribute authority or store receipts

Referenced implementation and authority layers:

- **Neurotransparency Doctrine (NTD):** epistemic rationale
- **Neurotransparency Specification (NTS):** enforceable disclosure requirements
- **Aurora Research Initiative (ARI):** governance authority
- **Aurora Workflow Orchestration (AWO):** methodology
- **Governance-Ledger:** authority publication and lineage
- **Contract Compiler:** compiled authority contract generation
- **Proposal Normalizer:** canonical proposal assembly
- **CRI-CORE:** deterministic admissibility kernel
- **Waveframe Guard:** runtime execution boundary
- **Waveframe Cloud:** authority distribution, registry, audit durability, and receipts

In the event of conflict, authority flows outward to the referenced specifications, releases, and implementation repositories, not inward to this website.

---

## Site Structure

The site consists of hand-authored static HTML files.

### Primary Pages

- `index.html` - product landing page and canonical architecture entry point
- `hierarchy.html` - governance execution architecture map
- `compatibility.html` - compatibility matrix and dependency specification
- `cri-core.html` - deterministic admissibility kernel
- `tools.html` - layered ecosystem and developer entrypoint
- `case-studies.html` - governed execution scenarios
- `updates.html` - protocol evolution and release engineering log

### Supporting Institutional Pages

- `doctrine.html` - Neurotransparency Doctrine
- `nts.html` - Neurotransparency Specification
- `ari.html` - Aurora Research Initiative governance
- `awo.html` - Aurora Workflow Orchestration methodology
- `publications.html` - canonical publications and DOI-backed artifacts

### Supporting Files

- `canonical-architecture.svg` - shared architecture diagram used by the website and README
- `waveframe-logo-mark.png`
- `waveframe-logo-full.png`
- `CNAME` - custom domain configuration
- `.nojekyll` - disables Jekyll processing
- `meta/VERSION.md` - website version contract
- `meta/SITE_LOG.md` - website deployment and structural change log

---

## Release Readiness

The v2.0.0 release is ready when:

- `meta/VERSION.md` declares current version `2.0.0`
- `meta/SITE_LOG.md` records the v2.0.0 structural release
- `index.html`, `hierarchy.html`, and `README.md` use `canonical-architecture.svg`
- `compatibility.html` is reachable from the primary navigation
- Core pages have no stale mojibake or pre-v2 architecture language
- Static preview verifies page load and responsive layout

---

## Editing and Deployment

Deployment is handled automatically via GitHub Pages.

1. Edit static files.
2. Commit to the deployment branch.
3. GitHub Pages redeploys automatically.

There is no build step, CI pipeline, or preprocessing layer. This is intentional and keeps the public reference surface directly auditable.

---

## Custom Domain Configuration

Waveframe Labs uses a custom domain managed via Porkbun.

### Apex A Records

```text
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

### CNAME

```text
waveframelabs.github.io
```

### Repository CNAME File

```text
waveframelabs.org
```

The `.nojekyll` file ensures files are served exactly as committed.

---

## License

- **Text and media:** CC BY-NC-SA 4.0
- **Code and scripts:** Apache 2.0

Where ambiguity exists, executable code is governed by Apache-2.0 and written or visual content is governed by CC BY-NC-SA 4.0.

Copyright 2026 Waveframe Labs.

---

## Governance and Contact

Waveframe Labs operates under the Aurora Research Initiative.

**Contact:** swright@waveframelabs.org  
**ORCID:** https://orcid.org/0009-0006-6043-9295
