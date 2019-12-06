---
title: Create blog posts and slides from the same Markdown file
sidebar:
  nav: modules
aside:
  toc: true
slides: default
---

If you often write blog posts on topics that you also give presentations on,
whether they are seminars, lectures, or workshops, it is useful to be able to
keep all information in one place, duplicating as little as possible. BlogSlides
helps you to do that.
<!--more-->

## Introduction

When I prepare a workshop, I often find that as well as slides I would like to
have a longer, blog post style, writeup of the content. This is partly because
writing everything down like that can help me clarify my thoughts and improve
the flow of the narrative, but also because it makes the content more accessible
to anyone who may want to study the subject by themselves.

The problem with this is that it leads to a lot of duplicated effort and makes
it difficult to work on both versions in parallel. BlogSlides is an attempt to
provide a solution to that problem. It combines [Jekyll](https://jekyllrb.com/)
(using the [TeXt](https://tianqi.name/jekyll-TeXt-theme/) theme), to create and
manage blog posts, with [reveal.js](https://revealjs.com/#/) for slides.
This has a number of advantages:

{% slide %}
{% slideonly %}
**Problem:** Creating blog post and slides for the same content can produce a lot
duplicate information that is hard to keep in sync.

**Solution:** Create a single Markdown file that contains both.

**Advantages:**
{% endslideonly %}

* Less duplication because some content can be reused directly.
* When different versions are required they are adjacent, simplifying the task
  of keeping them in sync.

{% endslide %}
