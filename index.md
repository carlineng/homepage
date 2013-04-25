---
layout: page
title: Vélo vos Liberabit
tagline:
---
{% include JB/setup %}

Welcome to my home on the web. I'm a data and analytics engineer, cyclist, and San Francisco resident.
Here, you'll find a collection of things that don't fit on [Twitter](https://twitter.com/carlineng/) or
[Instagram](http://instagram.com/carlineng).

![bike camping](/images/noah_and_nicole_black_mtn.jpg)

## Blog Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

