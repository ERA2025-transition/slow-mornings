# Slow Mornings — Landing Page

Free lead-magnet opt-in page for **Travel Adventures by Eunice** — *The Slow Morning Map* (7 European mornings). The conversion bridge from Pinterest/video into the email funnel.

- **Live (once enabled):** https://era2025-transition.github.io/slow-mornings/
- `index.html` — the standalone landing page.

## Before going live (do NOT enable Pages until these are done)
1. **Wire the form to Brevo.** Replace the placeholder `.opt` form with the Brevo double-opt-in embed (or point the form `action` at Brevo's hosted endpoint). Pass incoming pin **UTMs into Brevo hidden fields** so acquisition source survives to the confirmed contact and Email 2.
2. **Privacy policy live** (GDPR / Spain) — link the footer `Privacy` to it. Add FTC/AI disclosures as needed.
3. Then: make the repo **public** and enable **GitHub Pages** (deploy from `main`, root).

## Funnel continuity
Pinterest (Save this for your Europe trip →) → LP (You found one Slow Morning · Take all seven with you · Send me the Map →) → Brevo double opt-in → Email 1 → Email 2 (QS/BIS).

Design source of record: private `rms-board` repo, `ops/slow-mornings-30day/week0/`.
