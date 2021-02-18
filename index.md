---
layout: page
use-site-title: true
---

![logo](/assets/I_Logo_pleca_BANNER.png)

El Laboratorio Nacional de Ciencias de la Sostenibilidad (del [Instituto de Ecología, UNAM](http://web.ecologia.unam.mx/)) es una entidad académica de frontera al estar constituido como un nodo de generación, integración y síntesis que sirve de vínculo entre el ámbito académico, los tomadores de decisiones del sector público y los diversos sectores organizados de la sociedad. Así, el LANCIS está dirigido a ligar la ciencia y la toma de decisiones para facilitar el tránsito hacia la sostenibilidad en el país.

-----------

<style>
.aligned-row {
  display: flex;
  flex-flow: row wrap;

  &::before {
	display: block;
  }
}
</style>

<!-- tres columnas de showcase -->
<div class="container-fluid">
<div class="row aligned-row">
{% assign items = site.showcase %}
{% for item in items %}
<div class="col-sm-12 col-lg-12">
	<div class="panel panel-default">
		<div class="panel-heading">{{ item.title }}</div>
		<img src="{{ item.smallimg }}" width="100%" />
		<div class="panel-body">
			<p>{{ item.description }}</p>
			<p><a class="btn btn-default" role="button" href="{{ item.url }}">leer más &raquo;</a></p>
		</div>
	</div>
</div>
{% endfor %}
</div>
</div>
<!--
<a class="btn btn-default" role="button" href="/showcase">aún más...</a>
-->
-----------

## ¿Qué son las Ciencias de la Sostenibilidad?

Son una disciplina de investigación que estudia las interacciones
entre los sistemas naturales y sociales, así como la manera en que
dichas interacciones afectan la satisfacción de las necesidades de las
generaciones presentes y futuras. La investigación se lleva a cabo
dentro de un contexto de equidad y justicia social, buscando conservar
los sistemas de generación y mantenimiento de la vida en la Tierra.
Las Ciencias de la Sostenibilidad parten de un enfoque
transdisciplinario en el que lo cuantitativo y lo cualitativo, la
naturaleza y la sociedad, la teoría y la práctica se combinan.
Asimismo, retoman nociones y métodos de los sistemas complejos y
generan un enfoque de investigación que valora e integra el
conocimiento de los diferentes actores involucrados en un sistema
socioambiental y se centra siempre en la solución de los problemas
socioambientales que la motivan (Kates et al. 2001; De Vries, 2013;
González-Casanova, 2005).
