---
layout: post
title: Project
description: a project with no image
img: 
---

Every project has a beautiful feature shocase page. It's easy to include images, in a flexible 3-column grid format. Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so: 

	---
	layout: post
	title: Project
	description: a project with a background image
	img: {{ site.baseurl }}/img/12.jpg
	---

{% include album.html albumname="dogs" %}
