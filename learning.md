---
layout: default
title: learning
---
## [Learnings]({{title}})

<div>
  <ul class="posts">
  {% for post in site.posts %}
    {% if post.categories.first == "learning"  %}
      <li>
      <a href="{{ post.url }}"> {{ post.title }}</a> - {{ post.date | date: "%b %d, %Y"}}
      </li> 
    {% endif %}
  {% endfor %}
  </ul>
</div>