# Subodh Hande — Portfolio

Static site. No build step.

## Files that MUST be in the repo root
- `index.html`      ← the site (copy of `Portfolio.dc.html`)
- `support.js`      ← required runtime, loaded by index.html
- `.nojekyll`       ← stops GitHub Pages/Jekyll from mangling files
- `Subodh_Hande_Resume.pdf`
- `assets/subodh.jpg`
- `assets/logos/*.png`

## GitHub Pages
Settings → Pages → Source: **Deploy from a branch** → `main` / `/ (root)`.

If the page is blank, check the browser console:
- 404 on `support.js` → it wasn't pushed, or it's not next to `index.html`
- 404 on `assets/...` → folder casing must match exactly (`assets`, lowercase)
