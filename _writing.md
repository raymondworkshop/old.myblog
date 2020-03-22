---
layout: default
title: Reading
---

<div >
  <ul class="posts">
  {% for post in site.posts %}
    {% if post.categories contains 'writing'  %}
      <li>
      
      <small>{{ post.date | date: "%b %d, %Y"}}</small> <br>
      <a href="{{ post.url }}"> {{ post.title }}</a>  <br>   
          {{ post.abstract }} <br>
      
      </li>

    {% endif %}
  {% endfor %}
  </ul>
</div>