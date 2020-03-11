---
layout: default
title: "Resources"
permalink: /resources/
---

 {% for resource in site.resources %}

<div>
	<h2><a href="{{ resource.url }}">{{ resource.title }}</a></h2>
	<h4>{{ resource.excerpt | strip_html | strip_newlines | truncate: 200 }}</h4>
	<br><br>
</div>

 {% endfor %}
