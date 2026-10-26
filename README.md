# Victor's Handyman Services — website concept

Static homepage redesign of [repairrelief.com](https://repairrelief.com/), keeping the original site's copy, services, contact details and project photos. Built as a single `index.html` with no build step.

## Deploy

Every push to `main` runs `.github/workflows/deploy-pages.yml`, which publishes the site to GitHub Pages.
One-time setup: **Settings → Pages → Source: GitHub Actions**.

## Local preview

```bash
python3 -m http.server 8080
```
