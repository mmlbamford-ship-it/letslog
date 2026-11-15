# LetsLog website

Static site, no build step and no external requests (no fonts, scripts, cookies or analytics).

Files: `index.html`, `support.html`, `privacy.html`, `terms.html`, `legal.html`, `site.css`, `media/` (promo video, user guide video, posters, icon).

## Publish on GitHub Pages
1. Create a public repository named `letslog` under the account `mmlbamford-ship-it`.
2. Upload every file in this folder, keeping the `media` folder.
3. Repository Settings → Pages → Deploy from branch → `main`, folder `/ (root)`.
4. Live at https://letslog.co.uk (repository mmlbamford-ship-it/letslog, CNAME file in the root). DNS: 4 GitHub A records + www CNAME at Squarespace; letslog.uk forwards to letslog.co.uk. The app links to /privacy and /support.

## Before publishing
- `legal.html`: fill in the highlighted postal address (street, postcode and town). Add a VAT identification number later only if one is issued to you.
- Have the terms and legal notice checked by a lawyer; they were drafted without legal review.
- When the app is live, replace the "Coming soon · iPhone" pill with the App Store link.
