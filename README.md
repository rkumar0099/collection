# Contributors
{% for peer in site.stu %}
  <h2>{{ peer.name }} - {{ peer.user }}</h2>
  <p>{{ peer.content | markdownify }}</p>
{% endfor %}