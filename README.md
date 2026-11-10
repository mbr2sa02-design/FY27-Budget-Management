# Budget Monitoring FY27 (PWA)
Mongkol Borei 2 Community Engagement & Sponsorship Plan, Oct 2026 - Sep 2027.

## Publish on GitHub Pages
1. github.com > New repository (e.g. `budget-fy27`), Public (private needs a paid plan for Pages).
2. Upload all files in this folder (keep the `icons/` folder): Add file > Upload files > Commit.
3. Settings > Pages > Build and deployment > Source: Deploy from a branch > Branch: `main`, folder `/ (root)` > Save.
4. After 1-2 minutes open `https://<your-username>.github.io/budget-fy27/`.

## Install on a phone or computer
- Android/Chrome/Edge: menu > Install app (or Add to Home screen).
- iPhone/Safari: Share > Add to Home Screen.

## Notes
- Transactions are saved in the browser of each device (localStorage). Use **Export CSV** on the Actual Spending tab for backups.
- Plan numbers live in `index.html` (`const D=...`). To update the plan, ask Claude for a refreshed file, or edit that data.
- After changing files, bump `C='budget-fy27-v1'` in `sw.js` so installed copies refresh.
