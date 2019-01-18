---
---

# English2010
This is for writing assignments for my English 2010 Class!!

{% for coll in site.collections %}
{% unless coll.label == "posts" %}
{% for file in coll.files %}
<div>
  Name: {{ file.name }}
  Path: {{ file.path }}
</div>
{% endfor %}
{% endunless %}
{% endfor %}
