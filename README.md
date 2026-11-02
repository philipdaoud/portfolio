# Philip Daoud: Portfolio

Source for my personal portfolio site, served by GitHub Pages.

**Live:** https://philipdaoud.com

It's a single static page (`index.html`) with no build step and no dependencies. It has light and dark themes and works on mobile.

## Editing

- Content lives in `index.html`. Each section has an `id` (`work`, `experience`, `skills`, `learning`, `contact`).
- Images go in `assets/img/`.
- Preview it locally with `python3 -m http.server`, then open http://localhost:8000.

## Deploying

Go to **Settings → Pages → Build and deployment**, set it to *Deploy from a branch*, and pick `main` / `(root)`. The custom domain `philipdaoud.com` is set in the `CNAME` file.
