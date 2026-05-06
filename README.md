# Simply Jetpacks Website

The Simply Jetpacks website.

## Commands

Run these from the root of the project:

| Command        | Action                                 |
| :------------- | :------------------------------------- |
| `pnpm install` | Install dependencies                   |
| `pnpm dev`     | Start the Astro dev server             |
| `pnpm build`   | Build the production site into `dist/` |
| `pnpm preview` | Preview the built site locally         |

## GitHub Pages

Deployment is handled by the root workflow at `.github/workflows/ci.yml`.
It runs linting, type checking, and the Astro build on pull requests and on `main`, then deploys to GitHub Pages only from `main`.

The site is served from the custom domain `https://simplyjetpacks.com` via `public/CNAME`.
