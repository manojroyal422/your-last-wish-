YOUR LAST WISH — Cloudflare Workers deployment

This is a separate site from your AURELION watch website.

Files:
- public/index.html: complete website
- wrangler.jsonc: Cloudflare static assets configuration

GitHub / Cloudflare settings:
- Root directory: /
- Build command: leave empty
- Deploy command: npx wrangler deploy

Keep public/index.html at this exact path. The site uses external CDNs for fonts, Tailwind, and Three.js. Some features are demo/local-browser features until real backend, payment, booking, and media assets are connected.
