# charlie-tucker1.github.io

Personal site. Jekyll (built by GitHub Pages on push), geohot-style: monospace, white on black.

## Layout

- `index.html` — minimal homepage.
- `projects/index.html` — projects & research (the receipts page).
- `blog/index.html` — the blog, titled "i'm working on it". Lists everything in `_posts/`.
- `_posts/` — one Markdown file per post (create the folder with the first post).
- `_layouts/` + `assets/main.css` — the whole look (~40 lines of CSS; no theme).
- `papers/` — open-access PDFs.
- `_config.yml` — site config. Flip `url:` to the custom domain when DNS is live.

## To write a post

Create `_posts/2026-10-07-my-title.md`:

```markdown
---
layout: post
title: "My Title"
---
Markdown body. Code blocks, links, images all work.
```

Then `git ship "post: my title"`. GitHub builds and deploys in ~1 minute.
The filename date IS the post date; the URL becomes /blog/2026/10/07/my-title/.

## Rules

- Every number on the site traces to a repo README, a published paper, or a logged experiment.
- Draft posts: keep them OUT of `_posts/` until ready (a `drafts/` folder here is ignored by
  nothing — simplest is to write the file elsewhere and move it in when done).
