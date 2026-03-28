## Project

Static CV/resume site for alonisser, hosted on GitHub Pages.

## Structure

- `index.html` — Single-page CV with tabs, collapsible sections, CSS animations
- `stylesheets/` — CSS (github-dark theme, print, main stylesheet)
- `javascripts/main.js` — Tab switching and UI interactions
- `params.json` — Site metadata/parameters

## Branches

- `gh-pages` — Deployment branch (serves the site via GitHub Pages)
- `master` — Main development branch

## Development

No build step. Edit HTML/CSS/JS directly. Push to `gh-pages` to deploy.

## Gotchas

- The site uses `<details>` elements for collapsible sections — keep them for progressive enhancement
- Print styles are in `stylesheets/print.css` — verify print layout after changes
