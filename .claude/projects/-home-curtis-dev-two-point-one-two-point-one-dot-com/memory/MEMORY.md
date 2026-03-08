# Two Point One Analytics — Session Memory

## Project Status
- **Phase**: Migration complete — live on Cloudflare Pages
- **Last updated**: 2026-03-08

## Completed (2026-03-08)
- Migrated from Squarespace to Cloudflare Pages
- Built static single-page site (index.html + styles.css)
- Extracted CSS to separate file for maintainability
- Swapped font from Playfair Display → Hanken Grotesk
- Redesigned hero/footer with white overlays (light aesthetic)
- Circular headshot with name/title below, large statement text to right
- Client logos in infinite scrolling marquee
- Removed contact info (no email, no form — business card site only)
- Auto-deploy via Cloudflare Pages GitHub integration
- DNS pointed to Cloudflare Pages (custom domain live)

## Future Work
- Update tool logos (currently: GA, GTM, Fivetran, Domo, Tableau)
- Update services offered
- Refine layout / design tweaks
- Add favicon
- Add Open Graph / social meta tags

## Design Decisions
- Static HTML/CSS/JS only — no framework
- Cloudflare Pages for hosting (auto-deploy on push to main)
- Hanken Grotesk (Google Fonts) for both display and body text
- No contact info — site is a business card for existing contacts
- Separate `styles.css` for maintainability
