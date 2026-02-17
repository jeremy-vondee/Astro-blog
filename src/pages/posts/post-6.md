---
title: "Learning Astro Routing"
author: "Astro Learner"
description: "File-based routing makes it easy to understand where pages come from."
image:
    url: "https://docs.astro.build/assets/arc.webp"
    alt: "Paths branching out from the Astro logo."
pubDate: 2022-07-18
tags: ["astro", "routing", "fundamentals"]
---

Astro’s routing system is one of my favorite parts of the framework.

There’s no special routing config file to maintain. Instead, the folder structure inside `src/pages` directly controls the URLs for my site.

## What I learned

- `src/pages/index.astro` becomes `/`.
- `src/pages/about.astro` becomes `/about`.
- Nested folders create nested routes like `/blog/post-1`.

This model makes it very easy to answer the question: “Where does this page live?” Just follow the folders.
