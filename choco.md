---
layout: page
permalink: /choco/
title: choco milk files
description: A collection of chocolate milk and my thoughts on them.
---

<ul class="post-list">
{% for mname in site.choco reversed %}
    <li>
        <h2><a class="poem-title" href="{{ mnamee.url | prepend: site.baseurl }}">{{ mname.title }}</a></h2>
        <p class="post-meta">{{ mname.date | date: '%B %-d, %Y — %H:%M' }}</p>
      </li>
{% endfor %}
</ul>
