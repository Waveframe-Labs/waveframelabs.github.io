---
title: "Site Deployment Log - WaveframeLabs.org"
filetype: "documentation"
type: "log"
domain: "infrastructure"
version: "3.0.0"
status: "Active"
created: "2025-10-18"
updated: "2026-09-01"

author:
  name: "Waveframe Labs"
  url: "https://waveframelabs.org"

maintainer:
  name: "Waveframe Labs"
  url: "https://waveframelabs.org"

license: "CC-BY-NC-SA-4.0"

ai_assisted: "partial"

dependencies: []

scope:
  - "website deployment"
  - "public interface changes"
  - "release readiness"

authority_notes:
  - "This log records website-only deployments and structural changes."
  - "It does not constitute governance, doctrine, package, or research releases."
  - "Protocol and package release notes are surfaced in updates.html."

anchors:
  - "SITE-DEPLOYMENT-LOG-v3.0.0"
---

# Site Deployment Log - WaveframeLabs.org

Canonical append-only log recording public website deployments and structural changes for Waveframe Labs.

This log tracks:

- Website launches and redeployments
- Structural or navigational changes
- Public-facing content alignment
- Release-readiness alignment

This log does not record:

- Governance releases
- Research outputs
- Package publication events
- Internal drafts

---

## 2026-09-01 — Website v3.0.0 Institutional Redesign

- Restored `waveframelabs.org` as the canonical Waveframe Labs research and institutional surface.
- Separated research and product responsibilities between `waveframelabs.org` and `waveframelabs.com`.
- Replaced the product-led homepage with an institutional research narrative.
- Added `research.html` as the program map for ARI, AWO, Neurotransparency, and CRI-CORE.
- Added `about.html` for the organization, founder, contact, ORCID, and institutional boundary.
- Reframed `updates.html` as the canonical institutional and technical record and refreshed current public releases.
- Added the shared responsive institutional design system at `assets/institutional.css`.
- Normalized primary navigation across existing research and technical reference pages.
- Updated repository documentation and the website version contract to v3.0.0.
- Reclassified ARI and AWO as foundational maintenance-mode research and Neurotransparency as stable published research rather than current product dependencies.
- Removed the claim that Waveframe Labs or its current product runtime operates under ARI authority.

---

## 2026-05-18 - Website v2.0.0 Release Readiness

Prepared the website repository for the v2.0.0 public release.

Structural changes:

- Repositioned the homepage as the product landing page for deterministic execution-boundary enforcement.
- Added one canonical architecture diagram asset: `canonical-architecture.svg`.
- Embedded the canonical architecture diagram on the homepage and execution architecture page.
- Added `compatibility.html` as the compatibility matrix and dependency specification.
- Added Compatibility to the primary navigation across core pages.
- Reworked `hierarchy.html` into the governance execution architecture map.
- Reworked `tools.html` into the layered ecosystem and developer entrypoint.
- Reworked `cri-core.html` into the deterministic admissibility kernel page.
- Reworked `case-studies.html` into concrete governed execution scenarios.
- Reworked `updates.html` into the protocol evolution and release engineering log.
- Updated `README.md` for v2.0.0 architecture, scope, release-readiness checks, and supporting files.
- Updated `meta/VERSION.md` to declare current website version `2.0.0`.

Release-readiness checks:

- Core pages load in local static preview.
- Compatibility page is reachable from primary navigation.
- Homepage and architecture page share the same canonical diagram asset.
- Updated HTML/SVG release files have no detected mojibake artifacts.
- Temporary local preview server used for verification was stopped after testing.

---

## 2026-02-01 - v1.0.1 Patch Alignment

- Normalized institutional log and updates page to include:
  - Waveframe Labs Website v1.0.0 release
  - Waveframe Stamp v0.1.0 release
  - Waveframe Stamp v0.1.1 Zenodo DOI
- No layout or navigation changes.

---

## 2026-01-25 - Canonical Site Normalization and Structural Alignment

- Normalized global navigation to a single canonical menu across core pages.
- Rewrote homepage to reflect finalized Aurora layer ordering and authority boundaries.
- Corrected Aurora stack labeling and layer numbering for numerical and conceptual consistency.
- Standardized page structure, typography, and section hierarchy across core pages.
- Clarified separation between doctrine, specification, governance, methodology, tooling, and case studies.
- Added and normalized dedicated pages for Aurora Hierarchy, Tools and Infrastructure, and Canonical Updates Log.
- Established `updates.html` as the authoritative public-facing institutional log.
- Revised repository README to define canonical scope, authority limits, and versioning philosophy.

---

## 2025-10-19 - Content Refinement

- Updated homepage tagline for clarity.
- Refined CRI-CORE descriptive language.
- Added simulator-related keywords.
- Added Founder attribution section.

---

## 2025-10-18 - Homepage Expansion and Metadata Alignment

- Expanded homepage content:
  - About section
  - Research vs institutional pillars
  - Repository and demo links
  - Contact and citation references
- Surfaced ORCID and institutional contact email.
- Removed external email dependency.
- Corrected case-sensitive asset paths.
- Added OpenGraph and social preview metadata.
- Added site favicon.

---

## 2025-10-18 - Initial Public Deployment

- First production deployment of the Waveframe Labs website via GitHub Pages.
- Custom domain `waveframelabs.org` configured.
- HTTPS enabled via GitHub Pages.
- Dual licensing declared:
  - Code and scripts: Apache-2.0
  - Text and media: CC BY-NC-SA 4.0
- Initial landing page published with institutional mission overview, project cards, and navigation scaffolding.
- Created `meta/` directory for site metadata and logs.
- Added `.nojekyll` to ensure raw static file delivery.

---

Copyright 2026 Waveframe Labs.
