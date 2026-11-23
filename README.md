# Jawdat Faisal Al-Hussein — Portfolio

A responsive, dependency-free engineering portfolio built with semantic HTML, modern CSS, and vanilla JavaScript.

## Professional positioning

**Computer Engineer — Software, AI, Data & Embedded Systems**

The portfolio presents backend and application engineering, data platforms, applied machine learning, low-level programming, and foundational hardware–software integration. Embedded-systems work is described at a project level, including the documented Arduino calculator project and the CPython C-extension example.

## Included files

- `index.html` — complete portfolio website
- `Jawdat-Faisal-Al-Hussein-CV.pdf` — downloadable CV linked from the site
- `README.md` — project and publishing notes

## Responsive design and accessibility

The layout adapts across phones, tablets, laptops, and large desktop displays. It includes a compact mobile navigation menu, responsive project and repository grids, a mobile-friendly architecture explorer, theme switching, keyboard focus styles, and reduced-motion support.

The layout was checked in Chromium at viewport widths from **320px to 1920px**, including a landscape phone-sized viewport. Automated interaction checks covered mobile navigation, theme switching, all four architecture views, GitHub repository search and filters, and project-detail dialogs. No horizontal overflow or JavaScript page errors were found in those checks.

## GitHub repository explorer

The explorer renders the curated public repositories embedded in the page first, so repository cards, search, and language filters remain usable when GitHub is unreachable. The browser then makes an optional request to GitHub's public repositories API to enrich the catalogue with current repository metadata (such as languages, stars, and update dates) and additional public repositories. If the request fails or times out, the curated catalogue remains visible and interactive. No token or third-party JavaScript library is required.

## Publish with GitHub Pages

1. Put `index.html` and `Jawdat-Faisal-Al-Hussein-CV.pdf` in the root of the `jaudat150.github.io` repository.
2. Commit and push the files to the branch configured for GitHub Pages (commonly `main`).
3. In **Settings → Pages**, confirm that deployment points to that branch and `/ (root)`.
4. Open `https://jaudat150.github.io/` after the Pages deployment completes.

## Local preview

Open `index.html` directly in a browser, or run a local static server from this directory:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.
