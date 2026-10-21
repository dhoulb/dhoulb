# dhoulb.com

Personal site for Dave Houlbrooke. Built with [Astro](https://astro.build). Hosted on Cloudflare Workers (static assets).

## Commands

| Command          | Action                                  |
| ---------------- | --------------------------------------- |
| `npm install`    | Install dependencies                    |
| `npm run dev`    | Start local dev server at `localhost:4321` |
| `npm run build`  | Build the site to `./dist/`             |
| `npm run deploy` | Build and deploy to Cloudflare          |

## Deploy

Cloudflare Workers Builds deploys on every push to `main`. Build command: `npm run build`. Deploy command: `npx wrangler deploy`.
