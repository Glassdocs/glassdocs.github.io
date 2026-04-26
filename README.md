# Glassdocs - marketing site

Public marketing site for Glassdocs. Lives alongside `docs/`, `extension/`,
`brand/`, `templates/` in this repo. Separate from `docs/` (which is the
product's own documentation) and deliberately not built with the product's
own tooling - the product is for docs, the site is for marketing.

## Stack

Handwritten HTML + CSS. No framework, no build step, no dependencies.

## Preview

```
open site/index.html
```

That is the dev workflow.

## Structure

```
site/
  index.html           landing page (single-page)
  styles.css           all styles
  assets/
    logo-dark.svg      Rocket Lab wordmark, pre-colored for dark backgrounds
    logo.svg           original (uses currentColor, for reference)
    favicon.svg        favicon (Rocket Lab mint triangle)
    monogram.svg       standalone brand mark
```

## Deploy

`/.github/workflows/deploy-site-pages.yml` publishes `site/` to GitHub Pages
on every push to `main` that touches `site/`. Pages must be enabled in repo
Settings (Source: GitHub Actions) once the repo flips to public.
