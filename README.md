# portfolio018

Personal portfolio and blog built with [Hugo](https://gohugo.io/) and the [Hugo Profile](https://github.com/gurusabarish/hugo-profile) theme.

## Local preview

```bash
hugo server
```

Open the URL Hugo prints (usually `http://localhost:1313/portfolio018/`).

## Customize

- Site content (about, hero, projects): edit [`hugo.yaml`](hugo.yaml)
- Blog posts: `content/blogs/`

```bash
hugo new content blogs/my-post.md
```

## GitHub Pages

Built with Hugo in GitHub Actions (theme loaded as a git submodule). After the first workflow run:

1. Repo **Settings → Pages → Source → GitHub Actions**

Published at `https://thotran2015.github.io/portfolio018/`.
