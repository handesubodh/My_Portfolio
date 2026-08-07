# Subodh Hande — Portfolio Site

A single-file, no-build portfolio site styled as a technical blueprint / architecture
drawing set — fitting for a Generative AI Engineer who spends half the week drawing
system architectures for clients. Built from `Subodh_Hande_GenAI_Engineer_Resume_1770.docx`.

## What's inside

- `index.html` — the entire site (HTML + CSS + a few lines of JS). No build step, no dependencies to install.
- Signature element: an animated schematic diagram of the real multi-agent architecture
  built for the Tata Sons Deep Research AI platform, rendered as an SVG "wiring diagram."
- Sections: hero, spec strip, capability "bill of materials," a revision-history table for
  role progression at Bizmetric, eight project "drawing sheets," education plates and
  certification stamps, and a title-block footer with contact links.
- Respects `prefers-reduced-motion`, is keyboard-focus visible, degrades gracefully with
  JavaScript disabled (a `<noscript>` fallback and a 4s safety timer both guarantee content
  is never stuck hidden), and prints cleanly to PDF.

## Deploying to GitHub Pages

1. Create a new GitHub repository (public), e.g. `subodh-hande.github.io` (for a root user
   site) or any name like `portfolio` (for a project site).
2. Add `index.html` (and this `README.md`, optional) to the repo root and push:
   ```bash
   git init
   git add index.html README.md
   git commit -m "Add portfolio site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. On GitHub: go to the repo → **Settings** → **Pages**.
4. Under **Build and deployment**, set **Source** to `Deploy from a branch`, branch `main`,
   folder `/ (root)`. Save.
5. Wait ~1 minute, then your site is live at:
   - `https://<your-username>.github.io/` (if the repo is named `<your-username>.github.io`), or
   - `https://<your-username>.github.io/<repo-name>/` (for any other repo name).

No further configuration is needed — the page is a single static HTML file with fonts
loaded from Google Fonts over CDN.

## Editing content later

Everything lives in `index.html`. Content is grouped by section with clear id anchors
(`#hero`, `#skills`, `#experience`, `#projects`, `#education`, `#contact`) and comment
headers like `<!-- ============ PROJECT SHEETS ============ -->` to make it easy to find
what to change.
