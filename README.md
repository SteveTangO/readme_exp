# readme_exp

# contributors
{% for stu in site.stu %}
  <h2>{{ stu.name }} - {{ stu.position }}</h2>
  <p>{{ stu.content | markdownify }}</p>
{% endfor %}
