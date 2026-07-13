# manavgarg.github.io

Personal site — [manavgarg.github.io](https://manavgarg.github.io). Built with
Jekyll (custom minimal theme, no theme gem) and served by GitHub Pages.

## Writing a post

Add a markdown file to `_posts/` named `YYYY-MM-DD-slug.md` with front matter:

```yaml
---
layout: post
title: "Post title"
---
```

Outlines for future posts live in `_drafts/` — drafts never publish. To
publish one, move it to `_posts/` and add the date to the filename. Preview
drafts locally with `bundle exec jekyll serve --drafts`.

## Local development

```sh
bundle install
bundle exec jekyll serve   # http://localhost:4000
```
