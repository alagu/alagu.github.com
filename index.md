---
layout: default
title: Home
published: true
---

Hi there, I’m Alagu.

I’m an Engineer, Product guy – mostly a maker. I love building useful things. I’ve worked previously at Yahoo!, Zynga, Hackerrank and Practo. My first startup was [Markupwand](https://techcrunch.com/2012/08/17/markupwand), which was part of YCombinator Summer 2012.

Currently, I’m building [Peoplebox](https://www.peoplebox.ai) – a tool for building engaged & high-performing remote teams.

My interests are Products, Longevity, Yoga and Tamil Music.

### Newsletter

If you'd like to get an email when I write a post, subscribe here:

<div id="revue-embed">
  <form action="https://www.getrevue.co/profile/alagu/add_subscriber" method="post" id="revue-form" name="revue-form"  target="_blank">
    <div class="revue-form-wrap">
      <div class="revue-form-group">
        <input class="revue-form-field form-control" placeholder="Your email address" type="email" name="member[email]" id="member_email">
      </div>
      <div class="revue-form-actions">
        <input type="submit" value="Subscribe" class="btn btn-default" name="member[subscribe]" id="member_submit">
      </div>
    </div>
  </form>
</div>

### Posts

<ul>
  {% for post in site.posts %}
    <li>
      <span>{{post.date | date: '%B %Y'}}</span>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

### Elsewhere

- [Twitter](http://twitter.com/alagu)
- [Facebook](http://facebook.com/alagu)
- [LinkedIn](https://www.linkedin.com/in/alagu2/)
- [Github](https://github.com/alagu)
