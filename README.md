# rhizosat.com

Public website of **RhizoSat Analytics Pvt. Ltd.** - a single static page. No build step, no
JavaScript, no dependencies: the browser gets HTML, one stylesheet, three font files and two SVGs.

## Layout

| Path | Purpose |
|---|---|
| index.html | the whole page |
| styles.css | all styling, including the @font-face declarations |
| assets/contours.svg | generated topographic artwork behind the hero |
| assets/mark.svg | the monogram, used as favicon and in the header |
| assets/fonts/ | Fraunces (display) and Inter (text), self-hosted, both OFL |
| assets/og.jpg | social preview image, 1200x630 |
| _headers | security and caching headers, read by Cloudflare Pages |
| robots.txt, sitemap.xml | search engine plumbing |

## Deploying

Cloudflare Pages, connected to this repository:

- Framework preset: **None**
- Build command: **(empty)**
- Build output directory: **/**
- Production branch: **main**

Every push to main publishes. Pull requests get their own preview URL.

## Rules

1. **Nothing confidential here, ever.** This repository is public and its history is permanent.
   Marketing copy only - never a client name, a price, a strategy note or an internal link.
2. Brand decisions (palette, type, mark) live in the private company-os repository under
   brand/. This repository consumes them; it does not decide them.
3. Keep it dependency-free. If a build step ever becomes necessary, that is a decision to record,
   not a convenience to adopt.
4. The contact address is a placeholder: hello@rhizosat.com is not delivering mail yet.

## Editing copy

Everything visible is in index.html. The thesis line is
"Reports from orbit, decisions on the ground." - agreed 2026-10-16.
