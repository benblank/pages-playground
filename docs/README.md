## Are links rewritten?

[Does Liquid work in Markdown?](liquid-in-markdown.md)

## Pages

{% for page in site.pages %}
* {{ page.name }}
    * dir: {{ page.dir }}
    * path: {{ page.path }}
    * url: {{ page.url | relative_url }}
    * {{ page | jsonify }}
{% endfor %}
