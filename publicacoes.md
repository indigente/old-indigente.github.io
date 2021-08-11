---
layout: default
title: Publicações
permalink: /publicacoes/
---

# Publicações

Mais informações sobre as publicações estão disponíveis no [site antigo do Indigente](http://indigente.ufba.br/pt-br/papers).

{% for paper in site.data.publicacoes %}
- **{{ paper.title }}**, {{ paper.authors }}. {{ paper.event }} {{ paper.year }}{% endfor %}
