# readme_exp

# contributors
{% for stu in site.stu %}
  <h2>{{ stu.user }} - {{ stu.image }} - {{ stu.name }}</h2>
  <p>{{ stu.content | markdownify }}</p>
{% endfor %}
