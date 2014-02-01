<ul class="nav nav-pills">
{% for post in site.posts %}
  <li class="post">
    <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>

