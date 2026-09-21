# Daily Ascend — Landing page (English)

Static landing page (single-file HTML / CSS / JavaScript) for **Daily Ascend**, a pack of 2 Google Sheets trackers (habits + tasks) and 3 bonuses. English version for the anglophone markets (Kenya, Nigeria, Ghana, Tanzania, Rwanda, Uganda, Zambia).

## Contents
- `index.html` — the complete, self-contained page, ready to deploy (nothing to install).
- `.claude/launch.json` — local preview server config.

## Deployment (Vercel)
1. Import this repository into Vercel (or drop the folder).
2. No configuration needed: `index.html` is served at the root.

## Local preview
Serve the folder with any static server, e.g.:

```bash
npx serve -l 4322 .
```

## Notes
- Prices are shown in **USD** as a reference; Chariow converts to the buyer's local currency at checkout.
- The product / showcase images still contain French text and should be replaced with English versions.
