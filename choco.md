---
layout: page
permalink: /choco/
title: drink log
description: Files of different drinks and my thoughts on them.
---

<ul class="post-list">
{% for milkname in site.choco reversed %}
    <li>
        <h2><a class="milkname-title" href="{{ milkname.url | prepend: site.baseurl }}">{{ milkname.title }}</a></h2>
        <p class="post-meta">{{ milkname.date | date: '%B %-d, %Y — %H:%M' }}</p>
      </li>
{% endfor %}
</ul>
