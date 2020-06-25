---
layout: page
permalink: /choco/
title: choco milk files
description: A collection of chocolate milk and my thoughts on them.
---

<ul class="post-list">
{% for poem in site.choco reversed %}
    <li>
        <h2><a class="milkname-title" href="{{ milkname.url | prepend: site.baseurl }}">{{ milkname.title }}</a></h2>
        <p class="post-meta">{{ milkname.date | date: '%B %-d, %Y — %H:%M' }}</p>
      </li>
{% endfor %}
</ul>
