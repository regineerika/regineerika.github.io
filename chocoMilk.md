---
layout: page
permalink: /chocoMilk/
title: choco
description: Showcase your writing, short stories, or poems. Replace this text with your description.
---

<ul class="post-list">
{% for choco in site.chocoMilk reversed %}
    <li>
        <h2><a class="chocoMilk-title" href="{{ chocoMilk.url | prepend: site.baseurl }}">{{ choco.title }}</a></h2>
        <p class="post-meta">{{ choco.date | date: '%B %-d, %Y — %H:%M' }}</p>
      </li>
{% endfor %}
</ul>
