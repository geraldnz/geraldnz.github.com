---
layout: page
title: quotes
---

The terms used on this site are defined below.

 <ul>
 {% assign sorted_posts = (site.categories.['quotes'] | sort: 'title') %}
{% for post in sorted_posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
