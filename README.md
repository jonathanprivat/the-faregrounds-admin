# The Faregrounds — Admin CMS

Static admin panel served at **https://admin.nantucketfairgrounds.com/**.

Writes content changes to [`jonathanprivat/the-faregrounds`](https://github.com/jonathanprivat/the-faregrounds) (`public/data/site.json`) via the GitHub API, then GitHub Actions rebuilds and deploys the live site at [nantucketfairgrounds.com](https://nantucketfairgrounds.com).

## Architecture

- This repo hosts only the admin UI (single `index.html`).
- Shared static assets (images, fonts) are loaded from `nantucketfairgrounds.com` to keep a single source of truth.
- Deployment: GitHub Pages on `main` branch root.

## Editing

Changes to the admin panel itself happen here. Changes to site content happen through the live admin UI.
