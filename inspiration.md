---
layout: page
title: inspiration
---

The pages linked below offer insight into counselling, inspire or otherwise interest me.

<h3>quotations</h3>

<a href="http://gerald.nz/categories/quotes.html" title="Quotations">Quotations</a>

 <ul>
 {% assign sorted_posts = (site.categories.['quotes'] | sort: 'title') %}
{% for post in sorted_posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
