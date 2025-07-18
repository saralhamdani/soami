---
layout: default
title: Closets
permalink: /closets/
---

# Closets

Discover soami closets—each one shaped by the style of a different muse.

<ul>
  {% for closet in site.closets %}
    <li>
      <a href="{{ closet.url | relative_url }}"><strong>{{ closet.title }}</strong></a> &mdash; {{ closet.aesthetic }}
    </li>
  {% endfor %}
</ul>
