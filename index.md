---
layout: page
title: Home
---

# English2010
This is for writing assignments for my English 2010 Class!!

{% for page in site.pages %}
    ({{page.name}})[{{page.url}}]
    <a href="{{page.url}}">{{page.name}}</a>
{% endfor %}
