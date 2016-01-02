---
layout: page
title: categories
---

The pages related to site categories are linked, below.

<h3>CBT</h3>
 <ul>
 {% assign sorted_posts = (site.categories.['cbt'] | sort: 'title') %}
{% for post in sorted_posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>

<h3>Family Therapy</h3>
 <ul>
 {% assign sorted_posts = (site.categories.['familytherapy'] | sort: 'title') %}
{% for post in sorted_posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>

<h3>Narrative Therapy</h3>
 <ul>
 {% assign sorted_posts = (site.categories.['narrativetherapy'] | sort: 'title') %}
{% for post in sorted_posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>

<h3>Quotations</h3>
 <ul>
 {% assign sorted_posts = (site.categories.['quotations'] | sort: 'title') %}
{% for post in sorted_posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>

<h3>Terminology</h3>
 <ul>
 {% assign sorted_posts = (site.categories.['terminology'] | sort: 'title') %}
{% for post in sorted_posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
