---
title: "Rich Content"
date: 2026-05-10T12:00:00+06:00
draft: false
github_link: "https://github.com/Sayadbayezid/MusfiqRFarhan.blog"
author: "Sayad Md Bayezid Hosan"
tags:
  - Musfiq R Farhan
  - Portfolio
  - Rich Content
  - Media
image: "/images/post.jpg"
description: "Examples of rich embedded content and custom Hugo shortcodes."
toc: true
---

Hugo ships with several [Embedded Shortcodes](https://gohugo.io/content-management/shortcodes/#embedded) for rich content, along with a [Privacy Config](https://gohugo.io/about/privacy/#configuration) and a set of Simple Shortcodes that enable static and no-JS versions of various social media embeds.

## X Simple Shortcode

```text
{{</* tweet user="GoHugoIO" id="1315233626070503424" */>}}
```

<br>

{{< tweet user="GoHugoIO" id="1315233626070503424" >}}

<br>

## Vimeo Simple Shortcode

```text
{{</* vimeo 146022717 */>}}
```

<br>

{{< vimeo 146022717 >}}

<br>

## YouTube Simple Shortcode

```text
{{</* youtube w7Ft2ymGmfc */>}}
```

<br>

{{< youtube w7Ft2ymGmfc >}}

<br>

## Theme Custom Shortcodes

These shortcodes are not Hugo built-ins, but are provided by the theme.

### Responsive Images with Cloudinary

You can learn more about this [here](https://cloudinary.com/documentation/responsive_images).

Set the `cloudinary_cloud_name` parameter in your site config to use this shortcode.

```text
{{</* dynamic-img src="/my/image/on/cloudinary" title="A title for the image" */>}}
```

Note that you do not include the file extension (e.g. `.png`) in the `src` parameter, as the shortcode will automatically determine the best quality and format for the user's device.

Optionally, you can customize the general CSS styles for the image:

```text
{{</* dynamic-img src="/my/image/on/cloudinary" title="A title for the image" style="max-width:60%" */>}}
```
