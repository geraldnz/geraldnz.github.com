---
layout: page
title: timeline
---

The posts on this site are listed below in sequence from newer to older.
  
    {% for post in site.posts %}
  <ul><li>
    {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
  </li></ul>
  {% endfor %}
