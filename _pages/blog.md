---
title: "Blog sobre Córdoba"
permalink: /blog/
description: "Artículos sobre historia, patrimonio, rutas y curiosidades de Córdoba."
---

# Blog sobre Córdoba

Artículos para descubrir la historia, el patrimonio y los rincones de Córdoba antes o después de tu visita.

<div class="row">
{% for post in site.posts %}
  {% include main-loop-card.html %}
{% endfor %}
</div>