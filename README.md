# Logan King — Coaching Website

The website for SLKing, LLC — Logan King's coaching practice: individual work on the invisible beliefs running money, relationships, and confidence, plus high-stakes advisory for organizations.

**Live site: https://slkingco.com/** (custom domain on GitHub Pages; the old `sloganking.github.io/coaching/` URLs redirect here automatically.)

## Before editing any copy

Read [`writing-values.md`](writing-values.md) first and run its ship-tests. The site states; it doesn't convince. Copy that argues, hedges, or defends gets cut.

## Structure

- `index.html` — the whole main page, built around "powerful relationships" (Sep 24, 2026): hero, the two doors (Money, Intimacy), the reading-people engine line, a two-tap question flow (static JS, nothing stored; its only output is a prefilled `sms:` link), testimonials, crisis, bio + book, who it's for, CTA. The prior Seer version is preserved on branch `seer-site-before-powerful-relationships`.
- `work-with-me.html` — engagement tiers and pricing.
- `404.html` — branded not-found page.
- `writing-values.md` — the voice/values spec for all site copy.
- `logan.jpg`, `logan-portrait.jpg` (440px web copy used on the page), `favicon.png`, `apple-touch-icon.png`, `og-image.jpg` — photo and derived icon/link-preview assets.

## Deploying

Push to `main` → GitHub Pages rebuilds → live at slkingco.com in about a minute. Browsers may cache a page for up to 10 minutes; hard-refresh to see a fresh deploy immediately.

## Domain & DNS (GoDaddy)

- `slkingco.com` A records (`@`) → GitHub Pages IPs `185.199.108.153` / `.109.153` / `.110.153` / `.111.153`
- `www` CNAME → `sloganking.github.io`
- The `CNAME` file in this repo tells GitHub Pages which domain to serve.
- **Do not touch the MX/TXT records** — they route the logan@slkingco.com Google Workspace email.

## Contact

- Text/SMS: +1-865-456-8455
- Email: logan@slkingco.com

---

© 2026 SLKing, LLC
