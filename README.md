# Fortuna Private Wealth — Website

Static marketing site for **Fortuna Private Wealth, LLC**, an independent
fee-only registered investment adviser headquartered in Brickell, Miami.

This is a **draft** intended for review and revision before publication.
All names, biographical details, phone numbers, and the office address are
placeholders and must be replaced with the firm's actual information prior to
going live. The disclosure text is structured to match standard RIA practice
and tracks Form ADV, Form CRS, Regulation S-P (privacy), and Rule 206(4)-1
(the Marketing Rule), but it must be reviewed and approved by the firm's
Chief Compliance Officer before publication.

## Pages

- `index.html` — Home / hero
- `about.html` — Firm overview, philosophy, people placeholders
- `services.html` — Discretionary management, planning, concentrated-position
  work, multi-generational, cross-border, retirement-plan consulting
- `disclosures.html` — General disclosure, Form ADV, Form CRS, fiduciary duty,
  fees, conflicts, custody, privacy, business continuity, proxy voting,
  cybersecurity, Marketing Rule, jurisdiction
- `contact.html` — Brickell office placeholder, intake form, CCO contact

## Local preview

```bash
python3 -m http.server 4321
# then open http://localhost:4321
```

## Deployment

This site is suitable for GitHub Pages, Cloudflare Pages, Netlify, or any
static-file host. No build step is required.

## Before publishing — replacement checklist

- [ ] Replace the placeholder Brickell address with the firm's real address
- [ ] Replace `[Principal Name]` placeholders on `about.html` with real bios
      (or remove and link Form ADV Part 2B)
- [ ] Replace placeholder phone number (305) 555-0100
- [ ] Replace placeholder emails (`info@`, `compliance@`) with real addresses
- [ ] Add real Form ADV Part 2A / 2B and Form CRS files (linked from
      `disclosures.html`)
- [ ] Update jurisdictions where the firm is registered
- [ ] CCO review and sign-off on all disclosure language
- [ ] Confirm Marketing Rule compliance for any testimonials or third-party
      ratings added later
