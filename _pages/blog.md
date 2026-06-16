---
title: "Blog"
permalink: /blog/
description: "Artículos sobre historia, patrimonio, rutas y curiosidades de Córdoba."
---

# Blog sobre Córdoba

Artículos para descubrir la historia, el patrimonio y los rincones de Córdoba antes o después de tu visita.

{% for post in site.posts %}

## [{{ post.title }}]({{ post.url | prepend: site.baseurl }})

{% if post.description %}
{{ post.description }}
{% else %}
{{ post.excerpt | strip_html | truncatewords: 35 }}
{% endif %}

<small>{{ post.date | date: "%d/%m/%Y" }}</small>

---

{% endfor %}
