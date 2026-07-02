# GeoBee Brand Book — Static Site

A single, fully static `index.html`. No build step and no dynamic JavaScript — every logo is inlined as SVG and the layout is plain HTML/CSS. Fonts load from Google Fonts. Serve the whole folder as-is.

## Contents

- `index.html` — the entire brand book (one page)
- `.nojekyll` — tells GitHub Pages to serve files as-is
- `README.md` — this file

## Publish to GitHub Pages

1. Push the contents of this `site/` folder to a GitHub repository.
2. In the repo: **Settings → Pages**.
3. **Build and deployment → Source:** Deploy from a branch.
4. Pick the `main` branch and the `/ (root)` folder, then **Save**.
5. After ~1 minute the site is live at `https://<username>.github.io/<repo>/`.

## Local preview

Open `index.html` in any browser — no server required.

## Print / PDF

Use the browser's Print (Cmd/Ctrl-P) → *Save as PDF*. The page paginates onto US Letter with a repeating header/footer; enable **Background graphics** so colors print.
