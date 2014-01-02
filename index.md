---
layout: default
title: Welcome to Supper
---

{% include home.md %}

<ul>
{% for post in site.posts %}
  <li class="post">
    <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>
  </li>
{% endfor %}
</ul>