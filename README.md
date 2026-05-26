# Orda FinanceMFO Portal

Kazakhstan-style MFO landing portal for auto-secured loans, microloans, and entrepreneur support.

## Features

- Blue and gold Central Asia finance visual style
- Kazakh, Russian, and English language switcher
- Fully responsive layout for desktop and mobile
- Auto-secured loan, microloan, and SME finance modules
- Static loan calculator examples
- Static application/contact block
- Application process, reviews, FAQ, and compliance-style fine print
- Local hero visual asset, no required build step

## Deploy

This is a static site. Upload the project files to any static host, for example Nginx, Apache, Netlify, Vercel static output, Cloudflare Pages, or S3-compatible hosting.

For a quick local preview from this folder:

```bash
python -m http.server 4173
```

Then open:

```text
http://127.0.0.1:4173/
```

## Files

- `index.html` - page structure and content
- `styles.css` - responsive blue/gold business styling
- `script.js` - language switcher only
- `assets/hero-car-finance.png` - local hero image

## Integration Notes

The delivered version keeps only language switching as a front-end interaction. Calculator examples, FAQ, and contact/application blocks are static. Connect the contact block, calculator examples, or application CTA to CRM, SMS verification, scoring, or backend APIs only if a later interactive version is required.
