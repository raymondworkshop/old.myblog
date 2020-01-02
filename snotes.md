---
layout: default
title: Notes
---
<div >
  <ul class="posts">
  {% for post in site.posts %}
    {% if post.categories contains 'notes'  %}
      <li>
      
      <small>{{ post.date | date: "%b %d, %Y"}}</small> <br>
      <a href="{{ post.url }}"> {{ post.title }}</a>  <br>   
          {{ post.abstract }} <br>
      
      </li>

    {% endif %}
  {% endfor %}
  </ul>
</div>
