# GeoBee Brand Book — Static Site

A single, self-contained `index.html` — all fonts, scripts, and assets are inlined, so it works offline and needs no build step.

## Publish to GitHub Pages

1. Create a new GitHub repository and push the contents of this `site/` folder to it (`index.html`, `.nojekyll`, `README.md`).
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Choose the `main` branch and the `/ (root)` folder, then **Save**.
5. Wait ~1 minute. Your site will be live at `https://<username>.github.io/<repo>/`.

The included `.nojekyll` file tells GitHub Pages to serve the files as-is (skipping Jekyll processing).

## Local preview

Just open `index.html` in any browser — no server required.
