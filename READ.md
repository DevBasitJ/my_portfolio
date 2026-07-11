# AI Services Landing Page

A complete, single-file freelance landing page for an AI automation developer.
Built with vanilla HTML, CSS and JavaScript — no frameworks, no build step,
drag-and-drop deploy to Netlify or any static host.

## Live demo
[your-netlify-url.netlify.app](https://your-netlify-url.netlify.app)

## What's inside

- **Hero** — animated chat mockup + Finance Tools card + Neon Snake card stacked
- **What I build** — 6 capability cards with SVG icons
- **Industries** — 10 industry pills
- **ROI calculator** — 3 sliders, Rs/$ toggle, live cost estimate
- **Objection handler** — "I can just use AI myself" answered with 4 counter-points
- **Proof / Live work** — 3 shipped projects with real screenshots (✓ Shipped badges)
- **Try it live** — working Salahkaar AI shopping assistant (Claude API, 20-product catalog)
- **Finance Tools** — kharchay.pk screenshot embed with "Open full tool" link
- **Testimonials** — 3 client cards
- **Pricing** — Starter / Growth / Care Plan tiers
- **FAQ** — 6 questions, accordion + FAQPage JSON-LD schema
- **Process** — 4-step how it works
- **CTA** — email + WhatsApp contact

## Design system

| Token | Value |
|---|---|
| Primary | `#7C3AED` (violet) |
| Accent 1 | `#EC4899` (fuchsia) |
| Accent 2 | `#FB923C` (coral) |
| Gradient | `120deg, #7C3AED → #EC4899 → #FB923C` |
| Display font | Bricolage Grotesque |
| Body font | Plus Jakarta Sans |

## Built with
- Vanilla HTML / CSS / JavaScript
- Claude Sonnet 4.6 (Anthropic API) — powers the live Salahkaar assistant
- Google Fonts — Bricolage Grotesque + Plus Jakarta Sans
- No frameworks, no bundler, no dependencies

## Files
- `index.html` — the complete page (single file, ~320KB including embedded screenshots)

## Usage
1. Open `index.html` in any browser — works locally
2. To deploy: drag the file to [Netlify Drop](https://app.netlify.com/drop)
3. To enable Salahkaar with your own Worker: set `data-worker` on `#ldRoot` to your Cloudflare Worker URL