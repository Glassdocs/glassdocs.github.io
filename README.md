# glassdocs.github.io

Public marketing site for [Glassdocs](https://github.com/Glassdocs/glassdocs),
served at https://glassdocs.github.io.

Handwritten HTML and CSS. No framework, no build step, no dependencies.
The product itself is also handwritten HTML in `docs/` - eats its own
dogfood on the "zero build" philosophy of the product it advertises.

## Preview locally

```
open index.html
```

That is the dev workflow.

## Structure

```
index.html           landing page (single-page)
styles.css           all styles
assets/
  logo-dark.svg      Rocket Lab wordmark, pre-colored for dark backgrounds
  logo.svg           original (uses currentColor, for reference)
  favicon.svg        favicon (Rocket Lab mint triangle)
  monogram.svg       standalone brand mark
```

## Deploy

GitHub Pages auto-publishes the contents of this repo to
`glassdocs.github.io` on every push to `main`. No workflow needed -
org-pages repos serve directly from the default branch.

## License

MIT. By [Rocket Lab](https://rocketlab.com.au).
