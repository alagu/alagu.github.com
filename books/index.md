Pages

{% for page in site.page %}
{{ page.title }} ({{post.date | date: '%B %Y'}} )
{% endfor %}
