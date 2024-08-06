---
title: Blog
nav:
  order: 4
  tooltip: Announcements and News
---

# <i class="fas fa-feather-alt"></i>Blog

{% include section.html %}

{% include search-info.html %}

## News

{:.center}

{% include search-box.html %}

{% include tags.html tags=site.tags %}

{% include search-info.html %}

{% include section.html %}

{% include list.html data="posts" component="post-excerpt" %}
