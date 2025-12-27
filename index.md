---
layout: default
title: Home
---

# Welcome to My Website

This is a basic Jekyll site hosted on GitHub Pages.

## Getting Started

- Edit content in Markdown files
- Visit the [Jekyll documentation](https://jekyllrb.com) to learn more
- Browse the [GitHub Pages documentation](https://docs.github.com/en/pages)

## Latest Posts

{% for post in site.posts %}
  ### [{{ post.title }}]({{ post.url }})
  {{ post.excerpt }}
{% endfor %}
