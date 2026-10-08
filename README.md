# SEO, GEO &amp; PPC Portfolio - Sudhakar Murukuti

A single-page portfolio of SEO, GEO and PPC case studies, built as a static site for
GitHub Pages. No build step, no dependencies, just `index.html`.

**Live site (after you enable Pages):**
`https://mrsudhakar.github.io/seo-portfolio/`

## What's inside

- `index.html` - the whole portfolio (styles are inline, nothing else to load)
- `profile.webp` - profile photo, also used as the favicon
- `.nojekyll` - tells GitHub Pages to serve the files as-is
- 5 case studies: B2B SaaS (SEO + GEO), Programmatic SEO, FinTech revenue pages,
  D2C ecommerce, and School-admissions lead gen (SEO + Meta Ads)

## Enable GitHub Pages

1. Go to the repo on GitHub, then Settings, then Pages.
2. Under Build and deployment, Source, choose "Deploy from a branch".
3. Pick the branch that holds this site and the `/ (root)` folder, then Save.
4. Wait about a minute, then open `https://mrsudhakar.github.io/seo-portfolio/`.

## Edit the content

Everything lives in `index.html`:

- Add a case study: copy an existing `<div class="case"> ... </div>` block and update
  the title, meta line, challenge, strategy bullets and results list.
- Contact email (`murukuti.sudhakar@gmail.com`) appears in the header, the contact
  section, and the JSON-LD structured data. Update all three if it changes.
- Replace the photo by swapping `profile.webp` (keep the same filename).

## Preview locally

Open `index.html` in a browser, or run a tiny server:

```bash
python3 -m http.server 8000   # then visit http://localhost:8000
```
