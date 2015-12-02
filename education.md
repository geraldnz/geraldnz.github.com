---
layout: page
title: education
published: false
sitemap:
  lastmod: 2015-11-18
  priority: 0.7
  changefreq: 'monthly'
  exclude: 'no'
---


The pages related to this topic are linked, below.

 <ul>
 {% assign sorted_posts = (site.categories.['education'] | sort: 'title') %}
{% for post in sorted_posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
