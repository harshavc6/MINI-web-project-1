# MINI-web-project-1

Davie JR's Menu — a single-page burger menu built with plain HTML and CSS.

## 🔗 Live site

Hosted with GitHub Pages: **https://harshavc6.github.io/MINI-web-project-1/**

## Project structure

| File | Purpose |
| --- | --- |
| `index.html` | Page markup — nav bar, hero header, item description, order button, nutrition facts |
| `reset.css` | Eric Meyer's CSS reset for a consistent cross-browser baseline |
| `style.css` | Page styling — dark nav bar, hero image header, order button, responsive nutrition row |

## Running locally

No build step is required. Either:

- Open `index.html` directly in a browser, or
- Serve the folder so relative paths resolve exactly as they do on GitHub Pages:

  ```bash
  python3 -m http.server 8000
  ```

  then visit `http://localhost:8000/`.

## GitHub Pages setup

This site is published from the `main` branch using GitHub's standard
"deploy from a branch" flow, so it needs no workflow file or build step:

1. Go to **Settings → Pages** in this repository.
2. Under **Build and deployment → Source**, choose **Deploy from a branch**.
3. Set **Branch** to `main` and the folder to `/ (root)`, then **Save**.
4. GitHub publishes the site at `https://harshavc6.github.io/MINI-web-project-1/`
   within a minute or two. Re-check the Pages settings page for the exact
   status and URL.

Any push to `main` that touches `index.html`, `style.css`, or `reset.css`
automatically updates the live site — no redeploy step needed.
