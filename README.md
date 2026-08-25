# portfolio018

Personal portfolio site built with [Hugo](https://gohugo.io/).

## Local preview

```bash
hugo server
```

Open the URL Hugo prints (usually `http://localhost:1313/portfolio018/`).

## Add a project

```bash
hugo new content projects/my-project.md
```

Edit the front matter (`title`, `period`, `github`, `demo`, `image`) and writeup, then rebuild.

## GitHub Pages

This site is built with Hugo in GitHub Actions (not Jekyll). After the first workflow run:

1. Open the repo on GitHub → **Settings** → **Pages**
2. Set **Source** to **GitHub Actions** (not “Deploy from a branch”)

The site publishes at `https://thotran2015.github.io/portfolio018/`.
