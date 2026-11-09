# Marasi House — Concept Site

A single-page concept website for Marasi House (JVC, Dubai), built to show what a real
site for the restaurant could look like. No build step — `index.html` is a fully
self-contained static page (fonts load from Google Fonts; every photo and the logo are
embedded directly in the file).

## Run locally

Just open `index.html` in a browser — no server or install needed.

## Deploy on Netlify

**Option A — connect this GitHub repo (recommended, auto-deploys on every push):**

1. Push this repo to GitHub (see below).
2. On [netlify.com](https://app.netlify.com), click **Add new site → Import an existing project**.
3. Pick this repository. Build settings are already set via `netlify.toml`
   (publish directory `.`, no build command needed) — just click **Deploy**.

**Option B — drag and drop (fastest, no GitHub needed):**

Go to [app.netlify.com/drop](https://app.netlify.com/drop) and drag `index.html` onto
the page.

## Push this repo to GitHub

```bash
git init
git add .
git commit -m "Marasi House concept site"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

(Create the empty repo on GitHub first at github.com/new — don't initialize it with a
README, since this folder already has one.)

## Notes

- Hot Coffee menu prices are estimated — confirm against the real menu before sharing
  this with the client.
- Source screenshots used to build the page are kept locally but excluded from git via
  `.gitignore` (already baked into `index.html` as compressed images).
