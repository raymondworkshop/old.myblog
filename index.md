---
layout: default
---
<div>
  <ul class="posts">
  {% for post in site.posts %}
      {% if post.categories contains "home"  %}
      <li>
      <small>{{ post.date | date: "%b %d, %Y"}}</small> <br>
      <a href="{{ post.url }}"> {{ post.title }}</a>  <br>   
          {{ post.abstract }}  
      <!--
      <span class="archivedate hidemobile">{{ post.date | date: "%b %d, %Y"}}</span>
      -->
      </li>
          {% endif %}

  {% endfor %}
  </ul>

</div>



