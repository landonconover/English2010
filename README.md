# English2010
This is for writing assignments for my English 2010 Class

<ul>
{% for page in site.collections.legal.docs %}
  <li><a href="{{ page.url }}">{{ page.title }}</a></li>
{% endfor %}
</ul>
