# Personal Blog

A minimal Jekyll blog hosted on GitHub Pages.

## Write a post

Create a Markdown file in `_posts/` named `YYYY-MM-DD-slug.md`:

```markdown
---
layout: post
title: "Your title"
date: 2026-05-08
---

Your content in **Markdown**.
```

Commit and push to `main`. GitHub Pages rebuilds the site automatically.

## One-time setup

In the repo on GitHub: **Settings → Pages → Source: Deploy from a branch →
Branch: `main` / `(root)`**. After the first push to `main`, the site is
published at `https://<owner>.github.io/<repo>/`.

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

Open http://localhost:4000.

## Configuration

Edit `_config.yml` to change site title, description, author, or permalink
format.
