# newsite

One system, two surfaces:

- `index.html` — public site (Hrithick.xyz)
- `dashboard.html` — internal "Studio OS" dashboard for you and your team (served at `/dashboard`, noindex)

Both pages share a single runtime, `support.js`.

## Running locally

```
npx serve .
```

## Deploying

Static site, no build step. Deploy as-is to Vercel (or any static host) — `vercel.json` enables clean URLs so `/dashboard` works without the `.html` extension.
