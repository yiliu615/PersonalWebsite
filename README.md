# Yi Liu Personal Page
Website URL: https://gyang-eng.github.io/PersonalWebsite/

## GitHub Pages deployment
This repository includes a GitHub Actions workflow at `.github/workflows/deploy-pages.yml`
that deploys the static site to GitHub Pages whenever code is pushed to `main`.

### Recommended repository setting
In **Settings → Pages**, set **Source** to **GitHub Actions**.

This avoids branch-source confusion (for example, when working on non-`main` branches)
and makes deployment status visible in the **Actions** tab.

## Search indexing
To improve discoverability in search engines, this repository now includes:
- `robots.txt` allowing crawling and referencing the sitemap.
- `sitemap.xml` listing site URLs for indexing.
