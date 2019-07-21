---
layout: default
title: summary
---
## [summary]({{title}})

<div>
  <ul class="posts">
  {% for post in site.posts %}
    {% if post.categories.first == "summary"  %}
      <li>
      <a href="{{ post.url }}"> {{ post.title }}</a> - {{ post.date | date: "%b %d, %Y"}}
      </li>
    {% endif %}
  {% endfor %}
  </ul>
</div>