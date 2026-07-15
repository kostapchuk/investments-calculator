# Investment Calculator

A simple, client-side PnL / ROI / CAGR calculator. Enter multiple Buy/Sell
transactions (with dates), set your remaining holdings value, and it derives
the holding period and computes your results. No backend, no data leaves your
browser.

## Features

- Multiple dated Buy/Sell transactions (cash amounts)
- Auto-derived holding period from transaction dates
- PnL, ROI, CAGR with formula tooltips
- Light / dark theme toggle (persisted)

## Deploy to GitHub Pages

1. Create a new repository on GitHub.
2. Push this folder (must contain `index.html` at the root):
   ```bash
   git init
   git add index.html README.md
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/<your-user>/<repo>.git
   git push -u origin main
   ```
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to `Deploy from a branch`,
   choose the `main` branch and the `/ (root)` folder, then **Save**.
5. Wait ~1 minute, then visit:
   `https://<your-user>.github.io/<repo>/`

## Local use

Just open `index.html` in any browser — no server or build step required.
