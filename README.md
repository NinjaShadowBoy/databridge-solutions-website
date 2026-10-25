# DataBridge Solutions Website

A one-page marketing site for DataBridge Solutions, a (concept) agency that
offers digital marketing, CRM, SEO and process automation to banks. The page
has a hero section, services, pricing plans, benefits, and a contact form.

It is built with Angular 20 and deployed to GitHub Pages at
[ninjashadowboy.github.io/databridge-solutions-website](https://ninjashadowboy.github.io/databridge-solutions-website/).

The contact form is front-end only: it is not wired to any backend, so
submissions are not sent anywhere.

## Getting started

You need Node.js 20.19 or newer and [pnpm](https://pnpm.io) (the lockfile is
`pnpm-lock.yaml`).

```bash
git clone https://github.com/NinjaShadowBoy/databridge-solutions-website.git
cd databridge-solutions-website
pnpm install
pnpm start                 # dev server at http://localhost:4200
```

## Scripts

| Command | What it does |
|---|---|
| `pnpm start` | Dev server with live reload |
| `pnpm build` | Production build into `dist/databridge-solutions-website/` |
| `pnpm build:prod` | Production build with the GitHub Pages base path |
| `pnpm test` | Unit tests with Karma and Jasmine |
| `pnpm deploy` | Build for GitHub Pages and publish to the `gh-pages` branch |

## Where things are

The whole page lives in the root component: `src/app/app.html` for the markup
and `src/app/app.css` for its styles. Global styles are in `src/styles.css`.
