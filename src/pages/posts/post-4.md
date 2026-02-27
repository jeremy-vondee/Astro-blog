---
layout: ../../layouts/MarkdownPostLayout.astro
title: "Playing With Astro Components"
author: "Astro Learner"
description: "Small, reusable pieces that make my site feel well-structured."
image:
    url: "https://docs.astro.build/assets/arc.webp"
    alt: "Pieces of UI represented as glowing blocks."
pubDate: 2022-07-12
tags: ["astro", "components", "refactoring"]
---

Today I finally got comfortable with Astro components.

Instead of copying the same header code and navigation links into every file, I moved them into a `Header.astro` component and imported it wherever I needed it.

## What I built

I started with three components:

1. `Header.astro` for the site title and navigation.
2. `Footer.astro` for social links and credits.
3. `TagList.astro` to display the tags for each blog post.

Each component felt small and focused. That made it easier to read and test individually.

## The best part

Now when I want to tweak the navigation or change the site title, I only need to update one file. It makes my little blog feel maintainable, even as it grows.
