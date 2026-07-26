# The Bionic Builder

Website for **The Bionic Builder** — a guided founding cohort that helps independent artists build a complete, owned digital conversion machine (site, list, checkout, traffic) directed in plain English.

## Pages

| Path | Purpose |
|------|--------|
| `/` (`index.html`) | Main waitlist landing page |
| `/ladder.html` | Ownership Ladder opt-in squeeze page (primary paid-traffic destination) |
| `/ladder-confirmed.html` | Thank-you / reply-ask page after ladder opt-in |
| `/privacy.html` | Privacy Policy (draft) |
| `/terms.html` | Terms of Use (draft) |

## Stack

- Static HTML + Tailwind CSS (CDN)
- Brand tokens: ink `#07060b`, surface `#131c30`, gold `#e4c880`, cream `#f2efe6`
- Fonts: Bricolage Grotesque (headlines) + Inter (body)

## Placeholders still needed

| ID | Asset | Status |
|----|-------|--------|
| BB-A1 | Builder Portrait | Must shoot |
| BB-B1 | Migration Receipt | Screenshot |
| BB-C1 / BB-C1-M | Ownership Ladder poster + mockup | Design |
| BB-F1 | Wordmark lockup | Design |

## Launch blockers

1. Real Privacy + Terms (attorney glance)
2. Meta Pixel + Lead event on both forms
3. Form endpoint (Loops / ConvertKit / webhook) — ladder opt-in = waitlist join, tag `ladder-optin`
4. Vercel Analytics + UTM discipline
5. OG image (BB-C1 poster 1200×630 crop)
6. Clean URL rewrites (`/ladder` → `ladder.html`) if desired
