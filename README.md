# Khadga Consulting — khadgaconsulting.com

Marketing site for Khadga Consulting, a boutique network infrastructure
advisory firm founded by Chris Grundemann.

## Stack

Pure static HTML/CSS/JS. No frameworks, no build step, no dependencies
beyond Google Fonts (loaded via CDN).

## Deployment

Hosted on Cloudflare Pages. Push to `main` → deploys automatically.
Canonical domain: `https://www.khadgaconsulting.com`

## Structure

```
index.html        Single-page site — all content lives here
robots.txt
sitemap.xml
assets/           Logos, images, favicons, webmanifest
```

## Assets

- `Khadga_wht.png` / `Khadga-blk.png` — wordmark (nav, footer)
- `Logo_wht.png` / `Logo_blk.png` — full logo with sword mark
- `Mark_wht.png` / `Mark_blk.png` — sword mark only
- `philosopher.png` — hero background image
- `chris.svg` — headshot, Chris Grundemann section
- `og-image.png` — Open Graph / social share image (1200×630)
- `favicon.*` / `apple-touch-icon.png` / `site.webmanifest` — favicons

## Copy

All copy in `index.html` is final and approved. Do not edit without
review. The copy document history is maintained separately.

## Booking link

All CTAs point to `https://chrisgrundemann.com/meet`. Update here if
the booking URL changes.
