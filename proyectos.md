---
layout: page
permalink: /proyectos/
---

<div class="row">
{% for item in site.proyectos %}
<div class="col-lg-4">
<h2>{{ item.title }}</h2>
<p>{{ item.description }}</p>
  <p><a class="btn btn-default" role="button" href="{{ item.url }}">leer más &raquo;</a></p>
</div>
{% endfor %}
</div>
