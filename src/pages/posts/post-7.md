---
layout: ../../layouts/MarkdownPostLayout.astro
title: "Markdown and Content Collections"
author: "Astro Learner"
description: "Organizing my posts so they’re easy to query and display."
image:
    url: "https://docs.astro.build/assets/arc.webp"
    alt: "Markdown icons floating around the Astro logo."
pubDate: 2022-07-20
tags: ["astro", "markdown", "content"]
---

At first, I just dropped `.md` files into the pages folder. It worked fine for a tiny blog.

But then I discovered **content collections**, and everything clicked.

## Why collections help

With a collection, Astro can:

- Validate my frontmatter.
- Provide typed data for each post.
- Let me easily query all posts in a group.

It feels like having a mini CMS built right into the project. Now I can focus more on writing and less on wiring everything up by hand.
