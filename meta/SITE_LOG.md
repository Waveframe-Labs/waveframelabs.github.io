---
title: "Site Deployment Log — WaveframeLabs.org"
filetype: "documentation"
type: "log"
domain: "infrastructure"
version: "1.0.0"
status: "Active"
created: "2025-10-18"
updated: "2026-01-25"

author:
  name: "Waveframe Labs"
  url: "https://waveframelabs.org"

maintainer:
  name: "Waveframe Labs"
  url: "https://waveframelabs.org"

license: "CC-BY-NC-SA-4.0"

ai_assisted: "none"

dependencies: []

scope:
  - "website deployment"
  - "public interface changes"

authority_notes:
  - "This log records website-only deployments and structural changes."
  - "It does not constitute governance, doctrine, specification, or research releases."
  - "Institutional releases are recorded separately in updates.html."

anchors:
  - "SITE-DEPLOYMENT-LOG-v1.0.0"
---

# Site Deployment Log — WaveframeLabs.org

Canonical, append-only log recording **public website deployments and structural changes**
for Waveframe Labs.

This log tracks:
- Website launches and redeployments
- Structural or navigational changes
- Public-facing content alignment

This log does **not** record:
- Governance releases (see updates.html)
- Research outputs
- Tooling versions
- Internal drafts

---

## 2025-10-18 — Initial Public Deployment

- First production deployment of the Waveframe Labs website via GitHub Pages.
- Custom domain `waveframelabs.org` configured (Porkbun DNS).
- HTTPS enabled via GitHub Pages (Let’s Encrypt).
- Dual licensing declared:
  - Code & scripts: Apache-2.0
  - Text & media: CC BY-NC-SA 4.0
- Initial landing page published with:
  - Institutional mission overview
  - Project cards and navigation scaffolding
- Created `meta/` directory for site metadata and logs.
- Added `.nojekyll` to ensure raw static file delivery.

---

## 2026-01-25 — Canonical Site Normalization & Structural Alignment

- Normalized global navigation to a single canonical menu across all pages.
- Rewrote homepage to reflect finalized Aurora layer ordering and authority boundaries.
- Corrected Aurora stack labeling and layer numbering for numerical and conceptual consistency.
- Standardized page structure, typography, and section hierarchy across core pages.
- Clarified separation between:
  - doctrine
  - specification
  - governance
  - methodology
  - tooling
  - case studies
- Added and normalized dedicated pages for:
  - Aurora Hierarchy
  - Tools & Infrastructure
  - Canonical Updates Log
- Reframed tools descriptions to explicitly reflect subordinate, non-authoritative roles.
- Established `updates.html` as the authoritative public-facing institutional log.
- Revised repository README to define canonical scope, authority limits, and versioning philosophy.

---  

## 2025-10-18 — Homepage Expansion & Metadata Alignment

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

## 2025-10-19 — Content Refinement

- Updated homepage tagline for clarity.
- Refined CRI-CORE descriptive language.
- Added simulator-related keywords.
- Added Founder attribution section.

---
