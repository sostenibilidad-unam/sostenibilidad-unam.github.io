---
layout: page
title: "Showcase"
permalink: /showcase/
---

<div class="row">
{% for item in site.showcase %}
<div class="col-lg-4">
<h2>{{ item.title }}</h2>
<p>{{ item.description }}</p>
<p><a href="{{ item.url }}">{{ item.title }}</a></p>
</div>
{% endfor %}
</div>
