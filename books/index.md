# Book Notes

{% for category in site.categories %}
    <h3>{{ category | first }}</h3>
    {% for post in page.categories.category %}
      {{ post.title }}<br>
    {% endfor %}            
{% endfor %}
