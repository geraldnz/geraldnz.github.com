---
layout: page
title: inspiration
---

The pages related to this topic are linked, below.

 <ul>
 {% assign sorted_posts = (site.categories.['quotes'] | sort: 'title') %}
{% for post in sorted_posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
