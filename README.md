# Premium Brand Strategy Generator

Live site: **https://thekayradebe.github.io/brand-strategy-generator/**

A single self-contained HTML lesson page from the SMM Portfolio Challenge. No build
step, no dependencies. The only external thing it loads is Google Fonts.

## How to update it

1. Edit `index.html`
2. `git add -A && git commit -m "your message" && git push`
3. Wait ~60 seconds, then reload the live URL

## Where the original content lives

`index.html` was built from the lesson markdown. A copy of that source is kept here
in `source/01-brand-strategy.md` for reference. The HTML reworks some section titles
and adds a "Refine Your Deck" section, so the two are close but not identical.

The **canonical** copy — the one the content pipeline works from — lives outside this
repo at:

```
~/Documents/Other/portfolio-challenges/content/smm/01-brand-strategy.md
```

There is also a sales page draft alongside it in that folder
(`01-brand-strategy-sales-page.md`). It is deliberately **not** kept in this repo —
this repo is public, and everything in it is readable on the web.

If you regenerate the page from that pipeline, the output lands at
`~/Documents/Other/portfolio-challenges/output/smm/01-brand-strategy.html`.
Copy it over `index.html` here, then commit and push.

## Notes

- Hosting is GitHub Pages, serving branch `main` from the repo root.
- `.nojekyll` is present so GitHub serves the files as-is and does not try to
  process the markdown in `source/`. Do not delete it.
- This replaced an older static.app deployment, which stopped working.
