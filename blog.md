---
layout: page
title: blog
---

My posts of a more personal nature are listed below in sequence from newer to older.

 <ul>
 {% assign sorted_posts = (site.categories.['blog']) %}
{% for post in sorted_posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
