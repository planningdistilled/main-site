# planningdistilled.org

Static site served by GitHub Pages at https://planningdistilled.org/ (custom domain set by `CNAME`; DNS at Cloudflare).

- `research/england/` — England-wide work: `nppf-navigator/` (exported by `clav-planning/research/nppf-navigator`, `npm run export:pages`) and `service-village/` (built by `clav-planning/research/nppf-2026-decisions/analysis/service-village-page/build.mjs --pages`).
- `research/authority/<authority>/` — local planning authority reviews, e.g. `stratford-dc/`.
- `research/settlement/<settlement>/` — settlement case studies, e.g. `claverdon/`.
- Top-level paths (`/about`, `/contact`, `/blog`, …) are kept free for site pages.

The pages are generated in the `clav-planning` repo; edit them there and re-export. Update `lastmod` in `sitemap.xml` when a page changes.
The old addresses under `danmux.github.io/stratford-district-council/` redirect here.
