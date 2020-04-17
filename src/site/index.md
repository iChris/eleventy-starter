---
layout: home
title: Getting Your Voice Into the World
---

Welcome to Eleventy starter.


# Blog Posts

<ul>
{%- for post in collections.post -%}
  <li>{{ post.data.title }}</li>
{%- endfor -%}
</ul>