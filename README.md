# Cathena · front end

Options, made easy. One slider, max loss shown upfront, cash out any time, on Hyperliquid.

Static site for Vercel. The API, videos and `/watch` page are served by the Cathena backend
and proxied through Vercel (see `vercel.json`, added once the API domain is set), so everything runs on one domain.

- `index.html` – the app (mobile + desktop)
- `assets/` – logo and favicon

Deploy: import this repo in Vercel (framework preset: Other, no build command), then add your domain.
Generated from the main project with `scripts/build_frontend.sh`; edit there, not here.
