# MkDocs Shadcn GitHub Ready

Production-ready starter for documentation sites using `mkdocs-shadcn` and GitHub Pages.

## Features

- MkDocs + `theme: shadcn`
- GitHub Pages deployment via GitHub Actions
- Dark-friendly styling with a small custom CSS layer
- Clean navigation skeleton
- Search enabled
- Ready for docs growth: guides, API, changelog, releases

## Local development

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
mkdocs serve
```

## Build locally

```bash
mkdocs build
```

## Deploy

Push to `main`. The workflow in `.github/workflows/deploy.yml` publishes the site to GitHub Pages.

## First setup

1. Replace `USERNAME` and `REPO` in `mkdocs.yml`.
2. Update the site title, description, and logo if needed.
3. Add your content under `docs/`.
4. Commit and push.
