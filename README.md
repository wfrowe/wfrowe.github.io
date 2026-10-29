# wfrowe.github.io

Source for https://wfrowe.github.io. Built with [Astro](https://astro.build) and deployed to GitHub Pages by GitHub Actions on every push to `main`.

## Add a project

Create one Markdown file in `src/content/projects/`, for example `my-project.md`:

```md
---
title: Short, plain title
summary: One or two sentences on the question and the answer.
date: 2026-11-01
url: /my-project/        # optional: link to the project's own page
tags: [finance, maps]    # optional
draft: false             # optional: true hides it
---

Optional write-up. Used only when `url` is left out.
```

Push to `main` and the site updates in about a minute.

## Run locally

```
npm install
npm run dev      # preview at http://localhost:4321
npm run build    # production build into dist/
```

## Notes

- Public repo: nothing secret and no raw personal data goes in here.
- User site, so `astro.config.mjs` sets `site` and no `base`.
