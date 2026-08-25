# Tristan Cotino — Portfolio

> **Live site: [https://triscc.github.io/](https://triscc.github.io/)**

Personal portfolio website built with [SvelteKit](https://kit.svelte.dev/) and [Tailwind CSS](https://tailwindcss.com/). Showcases projects, creative pursuits, work experience, education, and contact details. Statically generated and deployed to GitHub Pages.

## Sections

- **Projects** — Odd Bird Out, Turff Mobile, Turff Tablet, Subreddit Language Lab, Clickbait Conundrum, and Creative Programming with P5.js
- **Creative Pursuits** — DJing, event management, and multimedia production
- **Work Experience** — Android/iOS development, Flutter, and customer support
- **Education** — MSc Creative Intelligence and Technology, BSc Computer Science
- **Contact** — LinkedIn, GitHub, and Instagram

## Tech Stack

- [SvelteKit](https://kit.svelte.dev/) (Svelte 5) with `@sveltejs/adapter-static`
- [Tailwind CSS](https://tailwindcss.com/) v4 with PostCSS
- [TypeScript](https://www.typescriptlang.org/)
- [Prettier](https://prettier.io/) with `prettier-plugin-svelte`
- Deployed via GitHub Actions to GitHub Pages

## Getting Started

```bash
npm install
npm run dev
```

## Scripts

| Command           | Description                         |
| ----------------- | ----------------------------------- |
| `npm run dev`     | Start the development server        |
| `npm run build`   | Build the static site into `build/` |
| `npm run preview` | Preview the production build        |
| `npm run check`   | Run `svelte-check` type checking    |
| `npm run format`  | Format code with Prettier           |
| `npm run lint`    | Verify formatting with Prettier     |

## Deployment

The site is automatically built and deployed to GitHub Pages by the workflow in [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml) whenever changes are pushed to `main`. The static adapter outputs to `build/`, which is uploaded as a Pages artifact.

## License

All content and code in this repository belong to Tristan Cotino.
