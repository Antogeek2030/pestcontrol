# Pest Control Victoria TX — Astro Site

Static Astro site for **pestcontrolvictoriatx.com**, optimized for Cloudflare Pages and fast Google indexing.

## Features
- Responsive, mobile-first design
- Green + amber color theme
- OpenStreetMap embed for 2301 E Mockingbird Ln, Victoria, TX 77904
- SEO: meta tags, canonical, JSON-LD LocalBusiness schema, sitemap, robots.txt
- Markdown blog with content collections
- Fast static build ideal for Google indexing
- Cloudflare Pages ready (static output, no adapter needed)

## Phone number
Placeholder: **(361) 555-0199** — replace across the project (search for `3615550199` and `555-0199`).

## Deploy to Cloudflare Pages
1. Push this folder to a GitHub/GitLab repo.
2. In Cloudflare Dashboard → Workers & Pages → Create → Connect to Git.
3. Build settings:
   - **Framework preset:** Astro
   - **Build command:** `npm run build`
   - **Build output directory:** `dist`
4. Add custom domain `pestcontrolvictoriatx.com`.
5. Submit `https://pestcontrolvictoriatx.com/sitemap-index.xml` in Google Search Console.

## Local development
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
```
Output is in `dist/`.

## Notes
- Fully static (`output: 'static'` by default) — ideal for Pages and SEO.
- `@astrojs/sitemap` generates `/sitemap-index.xml` at build time.
- `public/robots.txt` points crawlers to the sitemap.
- Blog posts live in `src/content/blog/*.md`.
