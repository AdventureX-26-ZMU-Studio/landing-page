# ZMU Studio

The source for [zmustudio.site](https://zmustudio.site) — an independent
three-person studio and AdventureX 2026 team.

## Local preview

This is a dependency-free static site. Serve the repository root with any local
HTTP server:

```bash
python -m http.server 4173
```

Then open `http://localhost:4173`.

## Deployment

GitHub Pages publishes the `master` branch from the repository root. No build
command is required. The custom domain is declared in `CNAME`, while Cloudflare
provides DNS for `zmustudio.site`.
