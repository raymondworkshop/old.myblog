---
layout: default
title: Diary
---

## [Diary]({{page.title}})
<!--
<ul class="archive">
    //    
     //   <li><a href="{{ item.link }}" title="{{ item.description }}" rel="external">{{ item.title }}</a></li>
    //   
</ul>
-->

<div class="postcontent archive">
  <ul class="archive">
  {% for post in site.posts %}
    {% if post.categories.first == "diary"  %}
      <li>
      <a href="{{ post.url }}"> {{ post.title }}</a>
      <span class="archivedate hidemobile">{{ post.date | date: "%b %d, %Y"}}</span>
      </li>
    {% endif %}
  {% endfor %}
  </ul>
</div>
