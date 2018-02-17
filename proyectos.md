---
layout: page
title: "Proyectos"
bigimg: /assets/F_edificio_lancis_BANNER.jpg
permalink: /proyectos/
---

<div class="row">
{% for item in site.proyectos %}
<div class="col-lg-4">
<h2>{{ item.title }}</h2>
<p>{{ item.description }}</p>
<p><a href="{{ item.url }}">{{ item.title }}</a></p>
</div>
{% endfor %}
</div>
