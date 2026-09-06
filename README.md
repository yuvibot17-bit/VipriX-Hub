# VipriX Hub

The official website for VipriX Hub — a static, single-page site with no build
step required.

## Structure

```
index.html              Page markup
assets/css/style.css    Styles
assets/js/script.js     Nav toggle, scroll effects, reveal-on-scroll
assets/images/logo.jpg  Brand logo (used as favicon, header, hero, footer)
```

## Running locally

No build tools or dependencies needed. From the project root:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` in a browser.

## Deploying

Any static host works as-is (GitHub Pages, Vercel, Netlify, Cloudflare Pages).
Point the host at the repository root — there is no build command to run.

## Editing content

- Copy, section order, and links live directly in `index.html`.
- Colors, spacing, and layout are controlled via CSS custom properties at the
  top of `assets/css/style.css`.
- Swap `assets/images/logo.jpg` to update the logo everywhere it appears.
