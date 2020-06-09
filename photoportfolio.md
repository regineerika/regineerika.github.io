---
layout: page
title: photoportfolio
permalink: /photoportfolio/
---


{% for image in site.static_files %}
<!--

    {% if page.galleries %}{% include image-gallery-index.html %}{% endif %}

<!--
-->
{% endfor %}


<!-- this is for the lightbox --> 
<script type="text/javascript" src="/js/lightbox.js"></script>
<link rel="stylesheet" href="/css/lightbox.css">
