# KANNALI GARAGE — Official landing website

A responsive static website for KANNALI GARAGE, Whitefield, Bengaluru. HTML/CSS/vanilla JS only. No build command, database or paid hosting required.

## Publish on GitHub Pages in 3 steps

1. **Create a repository** in your company-controlled GitHub account (suggested: `kannaligarage-website`). Upload the **contents** of this folder to the repository root (`index.html`, `css/`, `js/`, `assets/`, `README.md`).
2. **Enable GitHub Pages:** repository **Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save**. Wait for the deployment to finish; GitHub displays the website URL.
3. **Connect your domain:** in Settings → Pages enter `kannaligarage.com` under Custom domain. Follow GitHub's displayed DNS instructions at your current DNS provider, verify HTTPS and then select **Enforce HTTPS**. Do not modify your MX/SPF/DKIM email records. If using Cloudflare Pages instead, import the same repository as a Pages project (no build command; output directory `/`), then add your custom domain in Cloudflare.

## Local preview

Double-click `index.html` in a browser. For best results use `python -m http.server 8000` from this directory and visit http://localhost:8000.

## Important before publishing

- **Logo** is the user-supplied official image. Copyright © KANNALI Automotive. All rights reserved. Do not reuse outside authorized brand materials.
- **Gallery/service images** are intentionally self-contained, CSS-generated branded visual illustrations. They are **not real workshop photography**. No broken external image links or stock-photo licensing uncertainty. Replace these illustrations with approved original workshop photographs before presenting them as documentary photos.
- **Google rating 4.9 / 310+ reviews, CaRPM wording, operating hours and service claims** were provided by the website owner; independently verify they remain current before publication. Do not invent or publish customer testimonial quotes.
- **30-point inspection and technician certification** were not independently verified, so the copy avoids asserting those specific claims. Confirm them before adding them.
- **Free pickup** is explicitly subject to confirmation. Booking is a WhatsApp handoff, not a confirmed appointment. No prices or payment are collected.
- The Google Maps embed is a text search; confirm that it resolves to the correct business pin. Replace with an exact Google Maps Place embed if needed.
- Fonts load from Google Fonts; system fonts are used if unavailable. All other visuals and scripts are local.
- For SEO, if deploying under a `github.io` project subpath rather than `kannaligarage.com`, adjust the canonical and Open Graph URLs.
- Keep company account credentials, AWS secrets and API keys out of this public repository.

## Images and representation
Six realistic AI-generated workshop images are bundled locally as WebP. They are illustrative and do **not** document the actual KANNALI Garage premises, employees or customers. Google rating/review count should be checked against the live Business Profile before publishing.
