# Tatts by Munchkin

Website for **Tatts by Munchkin**, a home-based tattoo artist in the Manchester area of Richmond, VA.

- TikTok: [@tattsbymunchkin](https://www.tiktok.com/@tattsbymunchkin?_r=1&_t=ZP-99wxpHkwoLH)
- Payments accepted: Zelle, Apple Pay, Cash App, Venmo

## Structure

- `index.html` — all page content/sections
- `css/styles.css` — styling
- `js/script.js` — mobile nav toggle + footer year

## Editing content

Everything lives in `index.html`, organized by section:

- **Hero** — intro headline
- **About** (`#about`) — studio description and location
- **Pricing** (`#pricing`) — starting price tiers (edit the placeholder numbers to match real rates)
- **Pop-Up Deals** (`#deals`) — flash-deal callout
- **Payments** (`#payments`) — accepted payment methods
- **Book** (`#book`) — booking CTA linking to TikTok

## Running locally

No build step required — it's plain HTML/CSS/JS. Open `index.html` in a browser, or serve it:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploying

This is a static site, so it can be hosted for free with **GitHub Pages**:

1. Go to the repo's **Settings → Pages**
2. Under "Build and deployment", set **Source** to `Deploy from a branch`
3. Choose the `main` branch and `/ (root)` folder
4. Save — the site will be live at `https://<username>.github.io/<repo-name>/`
