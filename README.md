# Aliona Zayka — Portfolio

Static site (plain HTML/CSS/JS, no build step).

## Run locally
Open `index.html` in a browser, or run `npx serve .` in this folder.

## Publish
1. Create a new GitHub repository and upload everything in this folder (keep the `images` folder).
2. In Vercel: **Add New → Project → Import** the repo. Framework preset: **Other**. No build command, output directory: root.
3. Deploy. Every push to `main` redeploys automatically.

## Structure
- `index.html` — home
- `*.html` — case studies
- `images/` — all page images
- `vercel.json` — clean URLs (`/idt-byoc` instead of `/idt-byoc.html`)
