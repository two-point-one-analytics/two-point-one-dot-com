# Two Point One Analytics — Session Memory

## Project Status
- **Phase**: Initial setup / migration from Squarespace
- **Last updated**: 2026-03-08

## Completed
- Repo initialized with basic HTML and images (via Claude Desktop chat)
- Wrangler config added for Cloudflare Workers deployment
- README.md documented with project purpose and structure
- CLAUDE.md created with design/tool decisions
- Reviewed original Squarespace site at www.2point1analytics.com
- Fixed truncated index.html (completed script, closed body/html tags)
- Extracted CSS to separate `styles.css` file
- Fixed Cloudflare-obfuscated email → plain mailto link
- Replaced inline `document.write` year with `textContent` approach

## Known Issues
- Email in footer (`curtis@2point1analytics.com`) may need correction — was obfuscated in original
- No favicon
- No Open Graph / social meta tags

## Pending / Next Steps
- Confirm correct contact email address
- Match original Squarespace site design more closely
- Add favicon
- Add Open Graph meta tags
- Test Cloudflare Workers deployment (`wrangler dev`)
- Set up custom domain DNS

## Design Decisions
- Static HTML/CSS/JS only — no framework overhead for a single page
- Cloudflare Workers for hosting (fast, free tier, edge deployment)
- Separate `styles.css` for maintainability (multiple design changes planned)
- Email link only — no contact form needed
