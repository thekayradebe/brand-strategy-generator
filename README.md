# Premium Brand Strategy Generator

Live site: **https://thekayradebe.github.io/brand-strategy-generator/**

A single self-contained HTML lesson page from the SMM Portfolio Challenge. No build
step, no dependencies. The only external thing it loads is Google Fonts.

## How to update it

1. Edit `index.html`
2. `git add -A && git commit -m "your message" && git push`
3. Wait ~60 seconds, then reload the live URL

## Where the original content lives

`index.html` was generated from markdown lesson files. Copies of those sources are
kept here in `source/` for reference.

The **canonical** copies — the ones the content pipeline regenerates the HTML from —
live outside this repo at:

```
~/Documents/Other/portfolio-challenges/content/smm/01-brand-strategy.md
~/Documents/Other/portfolio-challenges/content/smm/01-brand-strategy-sales-page.md
```

If you regenerate the page from that pipeline, the output lands at
`~/Documents/Other/portfolio-challenges/output/smm/01-brand-strategy.html`.
Copy it over `index.html` here, then commit and push.

## Notes

- Hosting is GitHub Pages, serving branch `main` from the repo root.
- `.nojekyll` is present so GitHub serves the files as-is and does not try to
  process the markdown in `source/`. Do not delete it.
- This replaced an older static.app deployment, which stopped working.
