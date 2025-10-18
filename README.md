# Waveframe Labs

**Waveframe Labs** is the independent research initiative behind the *Waveframe Project* — a series of open, audit-first studies exploring entropy, information, and observer-driven cosmology.  
This site hosts public documentation and artifacts from the Waveframe research lineage.

🔗 **Live site:** [https://waveframelabs.org](https://waveframelabs.org)  
📄 **DOI (Zenodo):** [10.5281/zenodo.xxxxxxxx](https://doi.org/10.5281/zenodo.xxxxxxxx)

---

## Overview

This repository powers the [waveframelabs.org](https://waveframelabs.org) website using **GitHub Pages**.  
It’s a fully static, no-build deployment — just HTML, CSS, and Markdown.  
All files are served directly from the root branch.

---

## Editing Locally

1. Open `index.html` in a text editor.  
2. Make your edits or content updates.  
3. Commit and push to `main`.  
4. GitHub Pages will automatically redeploy.

> No Node, Jekyll, or build pipeline required.

---

## Custom Domain Configuration

The site uses a custom domain managed via Porkbun DNS.

- **A records (apex):**
  ```
  185.199.108.153
  185.199.109.153
  185.199.110.153
  185.199.111.153
  ```
- **CNAME (www):** `waveframelabs.github.io`

Ensure the file `CNAME` contains exactly:
```
waveframelabs.org
```

> `.nojekyll` disables Jekyll processing, allowing all directories to serve raw files.

---

## License

- **Text & Media:** [CC BY-NC-SA 4.0](LICENSE-NC.md)  
- **Code & Scripts:** [Apache 2.0](LICENSE)  
© 2025 Waveframe Labs. All rights reserved.

---

### Maintainer

**Shawn C. Wright**  
Independent Researcher · [ORCID 0009-0006-6043-9295](https://orcid.org/0009-0006-6043-9295)  
Contact: [swright@waveframelabs.org](mailto:swright@waveframelabs.org)
