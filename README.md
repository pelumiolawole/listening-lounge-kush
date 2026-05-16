# Listening Lounge by Kush

> A confidential online listening space for anyone carrying emotions in silence.

---

## Overview

**Listening Lounge by Kush** is a one-page landing site for a private 1-to-1 online emotional support service. The site is warm, intentional, and fully interactive — built to feel as safe and welcoming as the service itself.

- **Not therapy.** Not advice. Not judgement.
- Just a human being who will truly listen.

---

## Tech Stack

| Layer | Choice |
|---|---|
| Framework | Vanilla HTML / CSS / JavaScript |
| Fonts | Google Fonts (Cormorant Garamond + Inter) |
| Icons | Inline SVG (no external icon library) |
| Hosting | Vercel (static deployment) |
| Payments | PayPal (integrated via booking flow) |
| Scheduling | Calendly / Cal.com (to be embedded) |

---

## Project Structure

```
listening-lounge-kush/
├── index.html          # Single-page site (all markup, styles, scripts inline)
├── README.md           # This file
└── .gitignore          # Standard ignore rules
```

> **Note:** This is intentionally a single-file build for maximum portability and zero build-step complexity. All styles and scripts are self-contained.

---

## Getting Started

### Local Development

No build step required. Simply open `index.html` in any modern browser:

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/listening-lounge-kush.git
cd listening-lounge-kush

# Open in browser
open index.html
```

Or serve via a simple local server:

```bash
# Python 3
python -m http.server 3000

# Node (npx)
npx serve .

# PHP
php -S localhost:3000
```

### Deploy to Vercel

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel --prod
```

Or connect the GitHub repo directly via [vercel.com/new](https://vercel.com/new).

---

## Customization Checklist

Before going live, update the following placeholders:

- [ ] **Pricing** — Replace placeholder prices (`£35` / `£45`) with final rates
- [ ] **Booking Links** — Swap `alert('Booking system coming soon!')` with actual Calendly / scheduling embed
- [ ] **PayPal Integration** — Connect payment flow to live PayPal account
- [ ] **Social Links** — Update footer social icons with real Instagram / Twitter / LinkedIn URLs
- [ ] **Contact Email** — Add contact method if desired
- [ ] **Logo** — Replace inline SVG logo with actual brand asset if available
- [ ] **Meta Tags** — Update Open Graph / Twitter Card meta tags in `<head>`
- [ ] **Analytics** — Add Vercel Analytics, Plausible, or PostHog if tracking needed
- [ ] **Favicon** — Add `favicon.ico` and Apple touch icon

---

## Design Tokens

| Token | Value | Usage |
|---|---|---|
| `--cream` | `#F5F0E8` | Primary background |
| `--deep-brown` | `#2C1810` | Headings, dark sections |
| `--soft-gold` | `#C9A84C` | Accents, CTAs, hover states |
| `--warm-brown` | `#8B6914` | Secondary text, labels |
| `--taupe` | `#A08B7A` | Muted body text |

---

## Browser Support

- Chrome / Edge (last 2 versions)
- Firefox (last 2 versions)
- Safari (last 2 versions)
- Mobile Safari / Chrome

---

## License

Private — all rights reserved. Listening Lounge by Kush.

---

<p align="center">
  <em>Sometimes people don't need fixing. They just need someone who will truly listen.</em>
</p>
