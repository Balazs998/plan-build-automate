# Plan Build Automate

Static one-page site (plain HTML/CSS, no build step). `noindex, nofollow` is set; no analytics.

## Preview locally
    python3 -m http.server 8000   # open http://localhost:8000

## Deploy to GitHub Pages
1. Create a repository and push `index.html`, `styles.css` (screenshots optional).
2. Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
3. Site appears at `https://<user>.github.io/<repo>/`. Optional: add a `CNAME` file for a custom domain.

## TODO
- Replace the placeholder contact link in `index.html` with a form service or booking link.
- Example case studies are illustrative placeholders.
