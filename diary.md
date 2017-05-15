---
layout: default
title: diary
---

## [Diary]({{page.title}})
<br>
<!--
<ul class="archive">
    //    
     //   <li><a href="{{ item.link }}" title="{{ item.description }}" rel="external">{{ item.title }}</a></li>
    //   
</ul>
-->

<div>
  <ul class="posts">
  {% for post in site.posts %}
    {% if post.categories.first == "diary"  %}
      <li>
      <a href="{{ post.url }}"> {{ post.title }}</a> - {{ post.date | date: "%b %d, %Y"}}
      <!--
      <span class="archivedate hidemobile">{{ post.date | date: "%b %d, %Y"}}</span>
      -->
      </li>
    {% endif %}
  {% endfor %}
  </ul>
</div>
