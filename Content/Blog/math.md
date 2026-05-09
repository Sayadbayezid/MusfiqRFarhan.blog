---
title: "Render Math With MathJax"
date: 2026-05-10T12:00:00+06:00
draft: false
author: "Sayad Md Bayezid Hosan"
github_link: "https://github.com/Sayadbayezid/MusfiqRFarhan.blog"
tags:
tags:
  - Musfiq R Farhan
  - Portfolio
  - Blog
  - Media
  - Articles
  - Markdown Syntax
  - MathJax
  - Example
image: "/images/mathjax.png"
description: "Learn how to render mathematical equations using MathJax in Markdown and Hugo."
toc: true
mathjax: true
---

## MathJax

Math equations can be rendered using [MathJax](https://www.mathjax.org) syntax with AMS symbol support.

Optionally enable this on a per-page basis by adding `mathjax: true` to your frontmatter.

Then, use `$$ ... $$` on a line by itself to render a block equation:

$$ | Pr_{x \leftarrow P_{1}} [A(x) = 1] - Pr_{x \leftarrow P_{2}} [A(x) = 1] | < \text{negligible} $$

The raw version is:

```text
$$ | Pr_{x \leftarrow P_{1}} [A(x) = 1] - Pr_{x \leftarrow P_{2}} [A(x) = 1] | < \text{negligible} $$
```

Write in-line equations with `\\( ... \\)` , like \$begin:math:text$ x\^n \/ y \\$end:math:text$ . It's easy!

```text
Write in-line equations with `\$begin:math:text$ \.\.\. \\$end:math:text$` , like \\( x^n / y \\) . It's easy!
```
