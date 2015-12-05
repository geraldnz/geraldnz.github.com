---
layout: categories
title: quotations
---

Some of my favourite quotes follow:

 <ul>
 {% assign sorted_posts = (site.categories.['quotations'] | sort: 'title') %}
{% for post in sorted_posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>

