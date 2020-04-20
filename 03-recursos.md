---
layout: page
title: Recursos
permalink: /argentina-manuscrita-recursos/
type: extras
---


<!-- Recursos -->
<div class="container mx-auto px-2">
	<!-- <div class="border-top-thick">  Linea larga 
	<div class="col-1 sm-width-full border-top-thick"> </div> Linea corta -->
      <div class="py-1 mb-0 prose">
  <h2 class="h2 lh-condensed col-9 mb-2">
    <a class="no-underline" title="Texto anotado en Recogito" href="https://recogito.pelagios.org/document/wzqxhk0h3vpikm/part/1/edit" target="_blank">Texto anotado en Recogito</a>
  </h2>
  <a class="h3 lh-condensed" href="https://recogito.pelagios.org/document/wzqxhk0h3vpikm/part/1/edit" target="_blank"><p>El relato de Ruy Díaz de Guzmán disponible en una plataforma de anotación colaborativa</p></a></div>

	
  {% for post in site.recursos %}
    {% include post_block.html %}
  {% endfor %}

</div><!-- End Recursos -->