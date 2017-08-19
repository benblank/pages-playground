## Are links rewritten?

[Does Liquid work in Markdown?](liquid-in-markdown.md)

## Pages

{% for page in site.pages %}
* [{{ page.name }}]({{ page.url | relative_url }})
{% endfor %}
