# MLOPS Roadmap Site

This repository hosts a static site from `index.html` at the repository root.

## Local preview

From repo root:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000/`.

## GitHub Pages hosting

This repo includes a Pages workflow at:

- `.github/workflows/deploy-pages.yml`

To publish on GitHub Pages:

1. In GitHub, go to **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. Merge/push this branch to `main`.
4. Wait for the **Deploy static site to GitHub Pages** workflow to complete.
5. Open: `https://icosmic1.github.io/MLOPS/`.
