## Are links rewritten?

[Does Liquid work in Markdown?](liquid-in-markdown.md)

## Pages

{% for page in site.pages %}
* [{{ page.name }}]({{ page.url | relative_url }})
{% endfor %}

## Static Files

{% for static_file in site.static_files %}
* [{{ static_file.name }}]({{ static_file.url | relative_url }})
{% endfor %}
