# Galeria do Catetinho

Material de arquivo sobre o Catetinho.

{% for foto in site.foto %}
  <h3>{{ foto.title }}</h3>
  <p>{{ foto.date }} </p>
{% endfor %}
