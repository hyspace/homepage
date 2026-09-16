# homepage

hyspace's personal homepage, built with pure HTML and no CSS or client-side JavaScript.

Static files are stored in `public/` and deployed with Cloudflare Workers Static Assets.

Domain bindings are defined in `wrangler.jsonc`; the `www` redirect is managed by Cloudflare Redirect Rules.

## Local

```sh
pnpm install
pnpm dev
pnpm check
```

## Cloudflare

Use these settings when connecting the GitHub repository:

- Root directory: leave blank
- Build command: leave blank
- Deploy command: `pnpm exec wrangler deploy`
