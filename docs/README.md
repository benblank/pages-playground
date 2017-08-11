## Pages

{% for page in site.pages %}
* {{ page.name }}
    * dir: {{ page.dir }}
    * path: {{ page.path }}
    * url: {{ page.url }}
    * index: {{ page.index }}
{% endfor %}
