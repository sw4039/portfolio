# Sean Watson — Web Design Portfolio

Personal web design portfolio site. Static, single-page, fully self-contained HTML.

## Pages
- `public/index.html` — main portfolio (Web Studio)
- `public/logo.html` — SW logo page

## Hosting
Deployed on [Cloudflare Workers (static assets)](https://developers.cloudflare.com/workers/static-assets/), connected to this GitHub repo. Every push to `main` triggers an automatic deploy via `npx wrangler deploy`.

Config lives in `wrangler.jsonc` — it serves the `public/` directory as static files. No build step.
