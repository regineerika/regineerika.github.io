---
layout: page
title: photoportfolio
permalink: /photoportfolio/
---


{% for image in site.static_files %}
<!--
    {% if image.path contains 'photoportfolio' %}

-->
<div class="project">
    <div class= "thumbnail">
        <a href="{{ site.baseurl }}{{ image.path }}">
            <img class="thumbnail" src="{{ site.baseurl }}{{ image.path }}" />
        </a>
    </div>
</div>

<!--
    {% endif %}
-->
{% endfor %}




<!-- this is for the lightbox --> 
<script src="js/lightgallery.min.js"></script>
<link rel="stylesheet" href="css/lightgallery.css">
<script>
    lightGallery(document.getElementById('lightgallery'));
</script>
