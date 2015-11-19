---
layout: page
title: about
---

The pages linked below should give a brief introduction to me and my services.

 <ul>
 {% assign sorted_posts = (site.categories.['about'] | sort: 'title') %}
{% for post in sorted_posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
