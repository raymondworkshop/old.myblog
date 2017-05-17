---
layout: default
title: diary
---
## [Diary]({{title}})

<div>
  <ul class="posts">
  {% for post in site.posts %}
    {% if post.categories.first == "diary"  %}
      <li>
      <a href="{{ post.url }}"> {{ post.title }}</a> - {{ post.date | date: "%b %d, %Y"}}
      </li>
    {% endif %}
  {% endfor %}
  </ul>
</div>
