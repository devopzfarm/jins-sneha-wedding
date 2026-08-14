# Jins & Sneha — Wedding Invitation

Static invitation site for the Holy Matrimony of Jins Thomas and Sneha Elizabeth
Thomas on 7 November 2026 at Holy Cross Syro-Malabar Church, Kappadu, Kanjirappally.

Live at **https://jins-sneha-wedding.jinsthomas.dev**

## Layout

| File | Purpose |
| --- | --- |
| `index.html` | The whole invitation — cover, countdown, invitation, families, ceremony, closing |
| `d7.css` | All styling. Palette and type scale live in the `:root` block at the top |
| `wedding.js` | Countdown, "Add to Calendar", mobile nav and scroll reveals |
| `img/` | Photographs used by the page |
| `og-cover.jpg` | 1200×630 preview image for WhatsApp and social link previews |
| `CNAME` | Custom domain for GitHub Pages — do not delete |

## Editing

Ceremony time is marked with an `EDIT ME` comment in `index.html`. The wedding
date appears in `index.html` and in the countdown target inside `wedding.js`;
change both together.

## Deployment

GitHub Pages serves the `main` branch from the repository root, so pushing to
`main` publishes. Keep the Cloudflare DNS record for the subdomain set to
"DNS only" — proxying it prevents GitHub from renewing the HTTPS certificate.
