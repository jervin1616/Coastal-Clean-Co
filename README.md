# Coastal Clean Co.

Coastal Clean Co. — Spec portfolio project by Rising Tide Digital LLC. Demonstrates residential service business website design. Bright, lead-gen focused aesthetic. Built with plain HTML/CSS. Live at: [GitHub Pages URL]

## Pages

| File | Description |
|------|-------------|
| `index.html` | Homepage — hero, services strip, how it works, testimonials, trust section, CTA |
| `services.html` | Full service descriptions with task lists and per-service CTAs |
| `about.html` | Owner bio, values, team section |
| `contact.html` | Quote request form (Web3Forms) with sidebar contact info |
| `thanks.html` | Form confirmation page |

## Tech Stack

- Pure HTML5 / CSS3 / Vanilla JavaScript — zero frameworks or dependencies
- Google Fonts: Nunito (headings) + Inter (body)
- Form backend: [Web3Forms](https://web3forms.com) (replace `REPLACE_WITH_WEB3FORMS_KEY` in `contact.html`)
- Responsive: mobile-first, hamburger nav under 768px

## Colors

| Token | Value | Use |
|-------|-------|-----|
| White | `#FFFFFF` | Backgrounds, card surfaces |
| Sky Blue | `#E8F4FD` | Section accents, placeholders |
| Teal | `#0D9488` | Primary CTA, icons, accents |
| Navy | `#0B2545` | Headings, footer |
| Light Gray | `#F7F9FC` | Alternating sections |
| Warm Text | `#1A2A3A` | Body copy |

## Setup

1. Clone the repo
2. Replace `REPLACE_WITH_WEB3FORMS_KEY` in `contact.html` with your actual [Web3Forms access key](https://web3forms.com)
3. Open `index.html` in a browser — no build step needed
4. Deploy to GitHub Pages by enabling Pages on the `main` branch in repository Settings

## Deploy to GitHub Pages

```bash
git add .
git commit -m "Initial build"
git push origin main
```

Then go to **Settings → Pages → Source → Deploy from branch → main / root**.
