---
layout: default
title: language
---
## [Language]({{page.title}})
<!--
<ul class="archive">
    //    
     //   <li><a href="{{ item.link }}" title="{{ item.description }}" rel="external">{{ item.title }}</a></li>
    //   
</ul>
-->

<div>
  <ul class="archive">
  {% for post in site.posts %}
    {% if post.categories.first == "language"  %}
      <li>
      <a href="{{ post.url }}"> {{ post.title }}</a>
      <!--
      <span class="archivedate hidemobile">{{ post.date | date: "%b %d, %Y"}}</span>
      -->
      </li>
    {% endif %}
  {% endfor %}
  </ul>
</div>

