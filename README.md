# Security+ Sprint (static) — FIXED

This version fixes JSX braces and comments so the page renders when opened locally (with internet for CDNs).

## Quick Deploy (GitHub Pages)

1. Create a new repository named `securityplus-sprint` (public).
2. Upload these files to the repo root:
   - `index.html`
   - `robots.txt`
   - `sitemap.xml`
   - `.nojekyll`
3. Commit to the `main` branch.
4. Go to **Settings → Pages**:
   - **Source**: Deploy from a branch
   - **Branch**: `main` / `/ (root)`
5. Wait ~1–2 minutes, then open the Pages URL it shows.

If you see a blank page locally: open DevTools → **Console** to check for errors. Make sure you're online (CDN assets load).

## Custom Domain (optional)

- Set custom domain in **Settings → Pages**.
- DNS A records to GitHub Pages: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
- Add a `CNAME` file in the repo with your domain (e.g., `learnsecplus.uk`).

## Donations & Ads

- Replace donation links on the Support page with your handles.
- After AdSense approval, paste code into `#ad-top`, `#ad-mid`, `#ad-bottom`.

