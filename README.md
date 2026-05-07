# Pops — Single-page artist site

Rough draft for review. Built to deploy to GitHub Pages today, migrate to Carrd later.

## What's in this folder

- `index.html` — the whole site, single file, all CSS inline
- `images/` — placeholder photos of Pops's work
- `README.md` — this file

## Deploy to GitHub Pages (5 minutes)

1. Create a new GitHub repo (e.g. `pops` or `pops-art`)
2. Drop these files in the repo root (`index.html` and `images/` folder)
3. Push to `main`
4. In the repo: **Settings → Pages → Source: Deploy from a branch → Branch: main → /(root)** → Save
5. Wait 1–2 minutes
6. Site is live at: `https://[your-username].github.io/[repo-name]/`

## Generate the QR code

1. Once the site is live, copy the URL
2. Go to **qr-code-generator.com** or **qrcode-monkey.com** (free)
3. Paste URL, generate
4. Download as **SVG** (vector — uncle can scale it to any size cleanly)
5. Send to uncle for printing on cards / placards / stickers

## What's TODO before showing to the world

Search the HTML for `TODO:` comments — every one is a question for Pops or a placeholder to swap. Main ones:

- Real bio (in his voice)
- Hi-res photos of 6–9 best pieces
- Real Instagram handle
- Dedicated Gmail address
- Decide if commission section stays, goes, or moves to a Google Form
- Festival dates + location once known

## What's intentionally NOT here yet

- Print store link (waiting on print partner decision — INPRNT vs uncle vs both)
- Real form handlers (using `mailto:` for v1 — works on GitHub Pages with zero setup; can upgrade to Formspree or Google Forms later)
- Custom domain (free `username.github.io/popsart` URL is fine for v1; can buy domain later)
