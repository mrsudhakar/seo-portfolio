# SEO &amp; GEO Portfolio — Sudhakar Murukuti

A single-page portfolio of SEO, GEO and PPC case studies, built as a static site for
GitHub Pages. No build step, no dependencies — just `index.html`.

**Live site (after you enable Pages):**
`https://mrsudhakar.github.io/seo-portfolio/`

## What's inside

- `index.html` — the whole portfolio (styles are inline, nothing else to load)
- `.nojekyll` — tells GitHub Pages to serve the files as-is
- 5 case studies: B2B SaaS (SEO + GEO), Programmatic SEO, FinTech revenue pages,
  D2C ecommerce, and School-admissions lead gen (SEO + Meta Ads)

## Enable GitHub Pages

1. Go to the repo on GitHub → **Settings** → **Pages**.
2. Under **Build and deployment → Source**, choose **Deploy from a branch**.
3. Pick the branch that holds this site and the `/ (root)` folder, then **Save**.
   - Easiest path: merge this branch into `main`/`master` and serve from that branch's root.
   - Or serve directly from the `claude/gifted-pasteur-993oon` branch if you prefer.
4. Wait ~1 minute, then open `https://mrsudhakar.github.io/seo-portfolio/`.

## Edit the content

Everything lives in `index.html`:

- **Add a case study** — copy an existing `<article class="case"> … </article>` block,
  update the category, title, challenge, strategy bullets and the `.result` metric tiles.
- **Change a stat** — edit the `.num` / `.lbl` in the "At a glance" section, or the
  `.rnum` / `.rlbl` inside any case study.
- **Contact** — the email (`sudhakar@pathwaysmarketing.com`) appears in the hero,
  the contact section, and the JSON-LD structured data. Update all three if it changes.

## Preview locally

Just open `index.html` in a browser, or run a tiny server:

```bash
python3 -m http.server 8000   # then visit http://localhost:8000
```
