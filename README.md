# English2010
This is for writing assignments for my English 2010 Class

{% for file in site.static_files %}
        <a href="{{file.path}}">{{file}}</a>
{% endfor %}
