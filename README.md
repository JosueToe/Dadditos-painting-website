# Dadditos Painting LLC Website

Static multi-page site for **Dadditos Painting LLC** — interior & exterior painting in Palm Beach, Port St. Lucie, and Fort Lauderdale. Built for **Netlify** (no build step).

## Pages

- `index.html` — Home
- `services.html` — Interior & Exterior
- `gallery.html` — Contact/Gallery (phone, email, location) + project photos

## Local preview

Open `index.html` in a browser, or from the project root:

```bash
npx serve .
```

## Netlify deploy

1. Push this repo to GitHub (or drag the folder into [Netlify Drop](https://app.netlify.com/drop)).
2. In Netlify: **New site from Git** → pick the repo.
3. Build settings:
   - **Build command:** leave empty
   - **Publish directory:** `.` (or use `netlify.toml`, already set)
4. Deploy.

## SEO notes

Meta tags, Open Graph, Twitter cards, JSON-LD business schema, `robots.txt`, and `sitemap.xml` are included.

After you connect a custom domain on Netlify, update every `https://dadditospainting.com` URL in:
- page `<link rel="canonical">` / Open Graph tags
- [`sitemap.xml`](sitemap.xml)
- JSON-LD blocks in the HTML `<head>`

Then submit the sitemap in [Google Search Console](https://search.google.com/search-console).

## Brand & contact

| Item | Value |
|------|--------|
| Phone | (561) 460-3636 |
| Email | dadditospainting@gmail.com |
| Address | 4369 Tellin Ave, West Palm Beach, FL 33406 |
| Area | Palm Beach, Port St. Lucie & Fort Lauderdale |

Logo: `assets/logo.png` (transparent).  
Original gallery sources: `Gallery Images/` (web-optimized copies live in `assets/gallery/`).
