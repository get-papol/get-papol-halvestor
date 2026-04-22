# Halvestor Website

Landing page for Halvestor — Halal Investing Made Simple.

## Files
- `index.html` — main landing page (single file, no build step)
- `main.jpeg`, `main1.jpeg`, `1.jpeg`, `2.jpeg`, `3.jpeg`, `4.PNG` — app screenshots
- `Halvestor-cropped.svg`, `Halvestor (2)-cropped.svg` — logo files
- `favicon.ico`, `favicon.svg` — favicons

## To run locally
```
python3 -m http.server 8000
```
Then open http://localhost:8000

## Deployment
Drop the entire folder onto any static host — Netlify, Vercel, GitHub Pages, or Cloudflare Pages. No build step required.

## Mailchimp
Both email forms (hero + waitlist) post to the same Mailchimp list. Form action URL is in `index.html` on the `<form>` tags.
