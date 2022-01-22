
{% for category in site.categories %}
    <h3>{{ category | first }}</h3>
    {% for post in page.categories.category %}
      {{ post.title }}<br>
    {% endfor %}            
{% endfor %}


<ul>
  {% for post in site.posts %}
    <li>
      <span>{{post.date | date: '%B %Y'}}</span>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
