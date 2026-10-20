# visseo.info

Static website for Visseo (EN/DE/NL). Plain HTML, no build step.

## Deploy (Cloudflare Pages)
- Connect this repo under Workers & Pages -> Create -> Pages -> Connect to Git
- Framework preset: None
- Build command: (empty)
- Build output directory: `/`
- Production branch: `main`; other branches and PRs get preview URLs

## Layout
- `index.html` - landing page (all styles/scripts inline, i18n dictionaries at the bottom)
- `impressum.html`, `datenschutz.html`, `404.html` - legal pages and error page
- `fonts/` - self-hosted Space Grotesk, JetBrains Mono, Inter (OFL)
- `_headers`, `robots.txt`, `sitemap.xml`, `llms.txt` - hosting, crawler and AI-search files
- `og-image.png`, `mobile-first.png` - images

## Workflow
Work on a branch, check the preview URL, merge to `main` only when approved.
