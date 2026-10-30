# Plan Build Automate

Static one-page site (plain HTML/CSS, no build step). `noindex, nofollow` is set; no analytics.

The published site lives in `/docs` (`index.html`, `styles.css`, and `favicon.svg`). `README.md` and `screenshots/` stay at the repository root and are not part of the GitHub Pages site.

## Preview locally

From the `docs` folder:

    cd docs && python3 -m http.server 8000

Open http://localhost:8000

## Deploy to GitHub Pages

GitHub Pages deploys from the `main` branch, folder `/docs`.

1. Push this repository to GitHub.
2. Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/docs`.
3. The site appears at `https://<user>.github.io/<repo>/`. `docs/.nojekyll` is included so Pages serves the folder as plain files.

## TODO

- Add a form-service link in `docs/index.html` when a contact route exists (see the HTML TODO comment in the contact section).
- Example engagements are illustrative, not real client results.
