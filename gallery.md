---
layout: page
permalink: /gallery/
title: gallery
description: Something something
---

<ul class="post-list">
{% for gallery in site.gallery reversed %}
    <li>
        <h2><a class="gallery-title" href="{{ gallery.url | prepend: site.baseurl }}">{{ gallery.title }}</a></h2>
        <p class="post-meta">{{ poem.date | date: '%B %-d, %Y — %H:%M' }}</p>
      </li>
{% endfor %}
</ul>
