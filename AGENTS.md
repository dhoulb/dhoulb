# dhoulb.com

Personal site for Dave Houlbrooke. Built with [Astro](https://astro.build). Hosted on Cloudflare Workers (static assets).

## Commands

| Command          | Action                                  |
| ---------------- | --------------------------------------- |
| `bun install`    | Install dependencies                    |
| `bun run dev`    | Start local dev server at `localhost:4321` |
| `bun run build`  | Build the site to `./dist/`             |
| `bun run deploy` | Build and deploy to Cloudflare          |

## Deploy

Cloudflare Workers Builds deploys on every push to `main`. Build command: `bun run build`. Deploy command: `bunx wrangler deploy`. Cloudflare uses bun because `bun.lock` is present.

## Workflow

Push straight to `main`. Do not open pull requests. Fast development matters more than review on this project. Every push to `main` deploys to dhoulb.com, so run `bun run build` before you push.
