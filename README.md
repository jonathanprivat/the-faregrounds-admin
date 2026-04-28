# The Fairgrounds — Admin CMS

Static admin panel served at **https://admin.nantucketfairgrounds.com/**.

Writes content changes to the site repo (`public/data/site.json`), which then triggers an automated rebuild and deploy of the live site at [nantucketfairgrounds.com](https://nantucketfairgrounds.com).

## Architecture

- This repo hosts only the admin UI (single `index.html`).
- Shared static assets (images, fonts) are loaded from `nantucketfairgrounds.com` to keep a single source of truth.
- Deployment: static hosting on `main` branch root.

## Editing

Changes to the admin panel itself happen here. Changes to site content happen through the live admin UI.
