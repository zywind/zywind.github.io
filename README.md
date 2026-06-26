# zywind.github.io

Personal website of Yunfeng Zhang, built with [Hugo](https://gohugo.io) and the
[PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme.

## Develop locally

```bash
hugo server -D
```

Then open <http://localhost:1313>.

## Write a post

```bash
hugo new posts/my-post.md
```

Edit the file, set `draft: false`, then push to `master`. GitHub Actions builds
the site and deploys it to GitHub Pages automatically (see
`.github/workflows/hugo.yml`).

## Résumé

The PDF lives at `static/resume.pdf` and is served at `/resume.pdf`.

## Theme

PaperMod lives in `themes/PaperMod/`. To update it, replace that directory with a
newer release of the theme.
