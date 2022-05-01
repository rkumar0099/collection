# Contributors

{% for p in site.stu %}
  <a href="{{site.baseurl}}{{p.url }}"> {{ p.name }} </a> <br>
  <h2>{{ p.name }} - {{ p.user }}</h2>
  <p>{{ p.content | markdownify }}</p>
{% endfor %}