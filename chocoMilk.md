---
layout: page
permalink: /chocoMilk/
title: chocoMilk
description: Showcase your writing, short stories, or poems. Replace this text with your description.
---

<ul class="post-list">
{% for choco in site.chocoMilk reversed %}
    <li>
        <h2><a class="choco-title" href="{{ choco.url | prepend: site.baseurl }}">{{ choco.title }}</a></h2>
        <p class="post-meta">{{ choco.date | date: '%B %-d, %Y — %H:%M' }}</p>
      </li>
{% endfor %}
</ul>
