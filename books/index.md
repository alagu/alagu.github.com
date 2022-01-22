---
layout: page
title: Book Notes
---

<ul>
  {% for page in site.pages %}
    {% if page.categories contains "Books" %}
      <li>
        {{page.date | date: "%-d %b'%y"}} -
        <a href="{{ page.url }}">{{ page.title }}</a>
      </li>
    {% endif %}
  {% endfor %}
</ul>
