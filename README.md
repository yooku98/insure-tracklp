# Yooku InsureTrack — Landing Page

Marketing landing page for Yooku, a broker management platform for insurance brokers in Ghana and Africa: automated renewals, commission tracking and book-of-business management.

**Live site:** https://yooku.africa/

## What's on the page

- Product hero and feature overview
- Embedded product demo video (`InsureTrackDemo.mp4`)
- Onboarding steps and transparent pricing (from GHS 290/month)
- Call-to-action and support contact

## Stack

A single `index.html` with inline CSS/JS. No build step.

## Structure

```
index.html           Landing page
InsureTrackDemo.mp4  Product demo video
og-image.png         Social share image
favicon.svg / -32.png
CNAME                Custom domain (yooku.africa)
.nojekyll            Serve files as-is (skip Jekyll)
```

## Run locally

```bash
python3 -m http.server 8000
```

## Deployment

Served by GitHub Pages from `main` on the custom domain in `CNAME`. Don't remove `CNAME`.
