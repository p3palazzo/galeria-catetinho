---
title: "Galeria do Catetinho"
layout: home
date: 2021-09-09
---

Galeria de fotos históricas e documentos de arquivo sobre o Catetinho.

{% for foto in site.fotos %}
  <h3>{{ foto.title }}</h3>
  <p>{{ foto.date | date_format: "%d/%M/%Y" }} </p>
{% endfor %}

