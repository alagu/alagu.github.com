---
layout: default
title: Home
---

Hi there, I’m Alagu.

I’m an Engineer, Product guy – mostly a maker. I love building useful things. I’ve worked previously at Yahoo!, Zynga, Hackerrank and Practo. I also built my own startup – [Markupwand](https://techcrunch.com/2012/08/17/markupwand/), part of YCombinator Summer 2012.

Currently, I’m building [Peoplebox](https://www.peoplebox.ai) – a tool for building engaged & high-performing remote teams.

My interests are Products, Longevity, Yoga and Tamil Music.

## Posts

<ul>
  {% for post in site.posts %}
    <li>
      <span>{{post.date | date: '%B %Y'}}</span>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

## Elsewhere

- [Twitter](http://twitter.com/alagu)
- [Facebook](http://facebook.com/alagu)
- [LinkedIn](https://www.linkedin.com/in/alagu2/)
- [Github](https://github.com/alagu)
