---
title: "Understanding Astro Layouts"
author: "Astro Learner"
description: "How I used layouts to keep my pages consistent."
image:
    url: "https://docs.astro.build/assets/arc.webp"
    alt: "Curved shape glowing behind the Astro logo."
pubDate: 2022-07-10
tags: ["astro", "layouts", "learning in public"]
---

One of the biggest “aha!” moments I had with Astro was understanding layouts.

At first, I repeated the same header and footer on every page. It worked, but it felt messy and hard to maintain. Changing a single link meant editing multiple files.

Then I learned that I could create a **layout component** and use it as a wrapper around my content. Suddenly, everything became cleaner and easier to reason about.

## Creating my first layout

I created a file called `BaseLayout.astro` and moved my HTML structure there:

- The `<html>` and `<body>` tags.
- The header and navigation.
- A `<slot />` where each page’s unique content would go.

With that in place, each page became a lot simpler. Instead of building the full page, I only had to focus on the content that makes that page special.

## Why layouts matter

Layouts give me:

- Consistency across pages.
- A single place to update shared UI.
- A better mental model of my site.

It feels like my project grew up a little bit just by using them.
