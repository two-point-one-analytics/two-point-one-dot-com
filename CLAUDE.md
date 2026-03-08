# Project: Two Point One Analytics Website

## Architecture
- Static single-page site (HTML/CSS/JS) — no build step, no framework
- Deployed via Cloudflare Workers (static assets mode)
- Domain: www.2point1analytics.com

## Design
- Clean, minimalist, professional aesthetic
- Color palette: black text, white backgrounds, subtle grays
- Sans-serif typography
- Sections: Hero → Services → Tools → About → Clients → Footer
- Fade-in animations via IntersectionObserver
- Mobile-responsive grid layout

## Fonts
- Display + Body: Hanken Grotesk (Google Fonts)

## Conventions
- All images in `images/` directory
- `index.html` for markup, `styles.css` for all styling
- Minimal inline JS (fade-in observer, dynamic year)
- Google Fonts is the only external dependency

## Hosting
- Cloudflare Pages with GitHub integration (auto-deploy on push to main)
- `wrangler dev` for local development

## Notes
- No contact info — site is a "business card", not lead gen
- Not seeking new clients; site is for existing contacts' reference
