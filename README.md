# Alonisser CV

A GitHub Pages-based online CV/portfolio site.

**Live site:** [alonisser.github.io/cv](https://alonisser.github.io/cv/)

## How it works

This project uses GitHub Pages to serve a static CV site directly from the `gh-pages` branch.

- The **`gh-pages`** branch contains the actual site (`index.html`, stylesheets, etc.) - all content changes should be made there.
- The **`master`** branch contains this README only.

## Making changes

To update the CV content:

```bash
git checkout gh-pages
# edit index.html
git commit -am "feat: update cv"
git push origin gh-pages
```

The site will update automatically via GitHub Pages after pushing to `gh-pages`.
