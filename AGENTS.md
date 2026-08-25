# AGENTS.md

Guidelines for AI agents and developers working on this repository.

## Project Overview

Personal portfolio site for Tristan Cotino. Built with SvelteKit (Svelte 5) + Tailwind CSS v4, statically rendered to `build/` and deployed to GitHub Pages via GitHub Actions.

## Commands

- `npm run dev` — start dev server
- `npm run build` — static build output to `build/`
- `npm run preview` — preview production build
- `npm run check` — type check (`svelte-kit sync && svelte-check`)
- `npm run format` — format with Prettier
- `npm run lint` — verify formatting (`prettier --check .`)

Always run `npm run check` and `npm run lint` after making changes.

## Architecture

- `src/routes/+page.svelte` — single-page site; all sections (projects, creative pursuits, work experience, education, contact) live here
- `src/lib/Hero.svelte` — hero header component (uses `static/images/header.webp`)
- `src/lib/index.ts` — library barrel export
- `src/app.css` — global styles, Tailwind theme (custom colors: taupe, gunmetal, dim-grey, toffee, camel; dark mode via `dark:` variants)
- `static/images/` — project and hero images referenced by `/images/...` paths
- `svelte.config.js` — `adapter-static` with `pages: 'build'`, `fallback: '404.html'`; `paths.base = ''`
- `.github/workflows/deploy.yml` — CI/CD: builds and deploys to GitHub Pages on push to `main`

## Conventions

- Content is plain HTML/Svelte markup inside `+page.svelte`; add sections by copying the existing `<section id="...">` pattern and adding a nav link in the sticky header
- Use custom Tailwind palette classes (e.g. `bg-taupe-50 dark:bg-gunmetal-900`, `text-dim-grey-800`) — avoid arbitrary hex values except for image/gradient overlay styling
- Provide both light and dark variants (`dark:` prefix) for every styled element
- Images: add files to `static/images/` and reference as `/images/<name>`; `alt` text required
- External links open with `target="_blank" rel="noopener noreferrer"`
- Tabs for indentation, single quotes, Prettier formatting (`npm run format`)
- Do not commit to `main` directly unless it's a deployment; the workflow deploys on push to `main`

## Notes

- `base` path is empty locally; CI sets `BASE_PATH` for the GitHub Pages subpath (repo is `triscc.github.io`, so the deployed root matches `/`)
- `.nojekyll` in `static/` prevents Jekyll processing on Pages
