# Bilal Portfolio (GitHub Pages)

This is a single-file static site ready for GitHub Pages.

## Quick Deploy (no workflow)
1. Create a **public** repo on GitHub (any name, e.g. `bilal-portfolio`).
2. Upload these files to the repo root:
   - `index.html`
   - `.nojekyll`
   - `README.md`
3. Go to **Settings → Pages** → Source: **Deploy from a branch**.
   - Branch: `main`
   - Folder: `/ (root)`
4. Save. Open the URL GitHub shows (it will be `https://<username>.github.io/<repo>/`).

## Notes
- No build step; fully static.
- `.nojekyll` prevents Jekyll from ignoring folders that start with `_` (not used here but good practice).
- All links are anchors or absolute external links, so it works from any repo name (project pages) and from `username.github.io` (user pages).
