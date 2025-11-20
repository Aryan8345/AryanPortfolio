# AryanPortfolio

## Hosting

This repository contains a single-page portfolio `AryanPortfolio.html`. I added a GitHub Actions workflow to deploy this repository to GitHub Pages automatically on pushes to `main`.

What I added:
- `.github/workflows/deploy-pages.yml` — action that uploads the repo and deploys to GitHub Pages
- `index.html` — simple redirect to `AryanPortfolio.html` so the site loads at the repo root

To publish the site:

1. Commit & push the new files to `main` (the workflow triggers on push):

```bash
git add .
git commit -m "Add GitHub Pages workflow and index redirect"
git push origin main
```

2. After the push, visit the repository's Pages settings or the Actions tab. The `Deploy to GitHub Pages` workflow will run and publish the site. The Pages URL is typically `https://<your-username>.github.io/<repo-name>/`.

If you prefer a custom domain or different behavior (no redirect / different index file), tell me and I can update the workflow or index accordingly.

Arya Portfolio
