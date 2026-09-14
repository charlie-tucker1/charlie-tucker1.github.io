# charlie-tucker1.github.io

Personal site. Hand-written HTML, no build step, no dependencies, no tracker.

- `index.html` is the homepage; `style.css` is the shared stylesheet.
- `notes/` is the blog: one hand-written HTML file per post + `notes/index.html` as the list.
  To post: copy `notes/_template.html` to `notes/<slug>.html`, write, add one `<li>` to `notes/index.html`,
  then `git ship "post: <title>"`.
- `papers/` holds open-access PDFs (FLAIRS-39 paper is CC BY-NC 4.0).
- Content policy: every number on the page traces to a repo README, a published paper, or a logged experiment.
  Same receipts as the CV (`career-work/resumes/cv-master.md` is the shared source of truth).

Deploy: push to `main`; GitHub Pages serves it at https://charlie-tucker1.github.io.
