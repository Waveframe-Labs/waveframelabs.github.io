# Waveframelabs.org (GitHub Pages)

This is a **no-build** static site served by GitHub Pages.

## Local edit
Open `index.html` and push to `main`. No bundlers. No config.

## Custom domain
1. In repo **Settings → Pages**, set the custom domain to `waveframelabs.org`.
2. Create/keep a file named `CNAME` containing exactly `waveframelabs.org`.
3. DNS: point `@` to GitHub Pages A/AAAA records and `www` to `waveframelabs.github.io` (or your org handle).
4. After DNS propagates, enable **Enforce HTTPS**.

> Keep `.nojekyll` if you have folders that start with `_` (e.g., `_assets/`).