# planningdistilled.org

Static site served by GitHub Pages at https://planningdistilled.org/ (custom domain set by `CNAME`; DNS at Cloudflare).

- `research/england/` — England-wide work: `nppf-navigator/`, `dp3-design/` and `sustainable-location/` (with its sub-pages `sources/` and `service-village/`). `service-village/` holds only redirects to the page's new address.
- `research/authority/<authority>/` — local planning authority reviews, e.g. `stratford-dc/`.
- `research/settlement/<settlement>/` — settlement case studies, e.g. `claverdon/`.
- `research/england/nppf-navigator/decisions/` — a static page, and a Markdown copy, for every decision note behind the Navigator, with `decisions.json` and `decisions.csv`; `route/` is the Navigator's decision route as one page.
- `about/` — what the site is, the licence and how to reuse it. Other top-level paths (`/contact`, `/blog`, …) are kept free for site pages.

The research pages are generated from a separate working repository and exported here. A finishing pass in that repository then writes, on every page, the block between `<!-- pd:meta -->` markers (Open Graph tags, share image, structured data, dates) and regenerates `sitemap.xml`, `llms.txt` and `llms-full.txt`. Do not edit those by hand.

## For search engines and AI crawlers

- `robots.txt` welcomes every crawler, including AI training crawlers, and names the sitemap.
- `sitemap.xml` lists every page with the date its content last changed.
- `llms.txt` is a short guide to the site for language models; `llms-full.txt` is the decision route and every decision note as one text file.
- `.well-known/tdmrep.json` states that text-and-data-mining rights are not reserved.
- The 32-character `.txt` file at the root is the IndexNow key.

## Licence

Text, data and images on the site and in this repository are released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/): share and adapt freely, with credit to Planning Distilled. Quotations from decision letters, plans and the Framework remain their publishers' copyright. See `LICENSE`.
