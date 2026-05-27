# ModuleWarden landing page

Static marketing site. Single `index.html` file, Tailwind via CDN, no build step.

## Deploy

- GitHub Pages: `.github/workflows/pages.yml` deploys `docs/site` to `https://modulewarden.com` on pushes to `main`.
- Cloudflare Pages: `npx wrangler pages deploy docs/site` from repo root
- Local preview: `python -m http.server 8080 --directory docs/site`

See full deploy + form-wiring docs in the originating workspace at `kimiclaw/modulewarden-landing/README.md`.
