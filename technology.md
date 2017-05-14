---
layout: default
title: Science & Technology 
---
## [Science & Technology]({{page.url}})

<div class="postcontent archive">
  <ul class="archive">
  {% for post in site.posts %}
    
    {% if post.categories.first == "technology"  %}
      <li>
      
      <small>{{ post.date | date: "%b %d, %Y"}}</small> <br>
      <a href="{{ post.url }}"> {{ post.title }}</a>  <br>   
          {{ post.abstract }} <br><br>
      <!--
      <span class="archivedate hidemobile">{{ post.date | date: "%b %d, %Y"}}</span>
      -->
      
      </li>
    {% endif %}
  {% endfor %}
  </ul>
</div>