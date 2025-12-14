---
layout: page
title: Book Notes
---

<ul>
{% assign book_pages = site.pages | where_exp: "page", "page.categories contains 'Books'" | sort: "date" | reverse %}

{% for page in book_pages %}
  <li>
    {{ page.date | date: "%-d %b'%y" }} -
    <a href="{{ page.url }}">{{ page.title }}</a>
  </li>
{% endfor %}
</ul>

# Reading list

- [The Menu of Happiness](https://www.amazon.in/Menu-Happiness-Hisashi-Kashiwai/dp/103506071X)
- 
