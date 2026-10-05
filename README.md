# SYCZ Gold Duo — static landing-page MVP

## Files
- `index.html`: responsive landing page
- `styles.css`: dark gold/blue visual system and responsive styles
- `script.js`: mobile menu, reveal animations, optional outbound-event hook
- `privacy.html`: placeholder privacy page; must be revised before launch

## Preview
Open `index.html` locally in a browser, or run `python -m http.server 8000` from this folder and visit http://localhost:8000.

## Before deployment (important)
1. Telegram channel is linked in navigation, footer and final CTA: https://t.me/Syczfx. For purchase claims, keep using the described MQL5 messaging process unless you publish a verified alternative.
2. Confirm current MQL5 prices and product claims (sample values: $49 / $30); update all occurrences.
3. Obtain confirmation from MQL5 Service Desk on the permitted way to provide the additional EA. Replace provisional offer redemption text with the exact eligibility, delivery mechanism, wait time, activation and support terms. Do **not** advertise unapproved license transfers or delivery arrangements.
4. Confirm Meta ad eligibility in each targeted country, especially rules applicable to leveraged gold/CFD-related promotions.
5. Add actual product/logo/screenshots and real, context-rich performance evidence as appropriate; visual placeholders are illustrations, not trading performance.
6. Replace the placeholder privacy notice, configure a real custom domain, and add compliant tracking only after reviewing regional privacy/consent rules.

## Tracking
The site has no analytics integration by default. Clicks on links with `.outbound` dispatch a `sycz:outbound` CustomEvent containing `detail.product`. This is only a browser-side hook, not a recorded conversion, and does not verify purchases.

## Premium refinement edition
- Original screenshot-free design retained; improved typography, layout rhythm, responsive spacing, card interactions and restrained decorative motion.
- Thin scroll progress indicator and new locally bundled SVG favicon.
- Animations respect reduced-motion preferences; no third-party analytics added.
- Telegram: https://t.me/Syczfx
