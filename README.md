# Younghun Lee - Personal Academic Site

This repository is being migrated from a legacy Jekyll blog to an Astro-based personal academic website.

## Current status
- **Phase A complete**: New framework scaffold and core site architecture.
- **Phase B in progress**: Evergreen content migration started (about/research/notes/contact/CV structure + first migrated note).
- **Phase C started**: GitHub Actions workflow now builds Astro output from `dist/` and deploys to GitHub Pages.

## Run locally
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
```

## New information architecture
- `/` - Home
- `/research` - Research and projects
- `/notes` - Ongoing technical notes
- `/cv` - CV page
- `/contact` - Contact links

## GitHub Pages URL behavior
For a **user site** repository named `<username>.github.io`, the default URL remains:
- `https://<username>.github.io`

Switching from Jekyll to Astro does **not** change this URL by itself; it only changes the build pipeline.

## Legacy content
The legacy Jekyll files are still present in the repository for reference during migration.
