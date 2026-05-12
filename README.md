# green-scape-renewal
Landscape website renewal project.

## Preview

### 1) Local simple preview
Run a local server from the repository root:

```bash
python3 -m http.server 4173
```

Then open:

- http://localhost:4173/

### 2) GitHub Pages
This repository includes a GitHub Actions workflow at `.github/workflows/pages.yml` that deploys the static files in this repo to GitHub Pages.

- Enable **Settings → Pages → Build and deployment → Source: GitHub Actions**.
- Push to `main` (or run the workflow manually) to publish.
