# yiliu.github.io
Yi Liu's website

## GitHub Pages deployment
This repository includes a GitHub Actions workflow at `.github/workflows/deploy-pages.yml`
that deploys the static site to GitHub Pages whenever code is pushed to `main`.

### Recommended repository setting
In **Settings → Pages**, set **Source** to **GitHub Actions**.

This avoids branch-source confusion (for example, when working on non-`main` branches)
and makes deployment status visible in the **Actions** tab.
