# Jawdat Faisal Al-Hussein — Portfolio

A responsive, dependency-free portfolio built with semantic HTML, CSS, and vanilla JavaScript.

## Files

- `index.html` — portfolio website
- `Jawdat-Faisal-Al-Hussein-CV.pdf` — downloadable CV linked from the site

## GitHub repository explorer

The explorer renders a curated set of public projects from the page itself, so repository cards, search, and language filters still work when GitHub is unreachable. On page load, the browser makes one optional request to GitHub's public repositories API to enrich the catalogue with current repository metadata (languages, stars, and update dates) and any additional public repositories. If the request fails or times out, the bundled catalogue remains visible and interactive. No token or third-party JavaScript library is required.

## Publish with GitHub Pages

1. Put `index.html` and `Jawdat-Faisal-Al-Hussein-CV.pdf` in the root of the `jaudat150.github.io` repository.
2. Commit and push the files to the branch configured for GitHub Pages (commonly `main`).
3. In **Settings → Pages**, confirm that the deployment source points to that branch and `/ (root)`.
4. Open `https://jaudat150.github.io/` after the Pages deployment completes.

## Local preview

Open `index.html` directly in a browser, or run a local static server from this directory:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.
