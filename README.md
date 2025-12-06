# Waveframe Labs — Website Repository

This repository hosts the static website for **Waveframe Labs**, the independent research institute operating under the **Aurora Research Initiative (ARI)**.  
The site provides public documentation, institutional references, and project overviews for the Aurora ecosystem — including the **Aurora Hierarchy**, **Neurotransparency Doctrine & Specification**, **AWO**, **CRI-CORE**, and active case-study research.

**🔗 Live Site:** https://waveframelabs.org  
**🏛 ARI DOI:** https://doi.org/10.5281/zenodo.17743096

---

## Purpose of This Repository

This repository contains the full source of the Waveframe Labs website.  
It is intentionally designed to be:

- **fully static**  
- **no-build / no-framework**  
- **GitHub Pages–native**  

The goal is deterministic transparency: every rendered page is directly visible in the repository and audit-ready.

---

## Site Structure

The site is composed of hand-authored static files:

### **Primary Pages**
- `index.html` — homepage & institutional overview  
- `ari.html` — Aurora Research Initiative  
- `hierarchy.html` — the six-layer Aurora architecture  
- `doctrine.html` — Neurotransparency Doctrine  
- `awo.html` — Aurora Workflow Orchestration  
- `cri-core.html` — enforcement layer (CRI-CORE)  
- `case-studies.html` — active and archived case studies  
- `tools.html` — organizational tooling

### **Supporting Files**
- `waveframe-logo-mark.png`  
- `waveframe-logo-full.png`  
- `meta/` — site logs and metadata  
- `CNAME` — required for custom domain  
- `.nojekyll` — ensures raw file delivery

---

## Editing & Deployment

Deployment is automatic via GitHub Pages.

1. Edit any `.html` file (e.g., `index.html`).  
2. Commit changes to `main`.  
3. GitHub Pages redeploys immediately.

There is **no CI pipeline, bundler, or build step** — by design.  
This maintains deterministic, transparent behavior aligned with **Neurotransparency** and **ARI** governance requirements.

---

## Custom Domain Configuration

Waveframe Labs uses a custom domain via Porkbun.

### **Apex A Records**
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

### **CNAME (www)**
```
waveframelabs.github.io
```

### **CNAME file content**
```
waveframelabs.org
```

The `.nojekyll` file disables Jekyll processing, ensuring all files are served exactly as written.

---

## License

- **Text & Media:** CC BY-NC-SA 4.0  
- **Code & Scripts:** Apache 2.0  

© 2025 Waveframe Labs.

---

## Governance & Contact

Waveframe Labs operates under the Aurora Research Initiative.

**Email:** swright@waveframelabs.org  
**ORCID:** https://orcid.org/0009-0006-6043-9295
