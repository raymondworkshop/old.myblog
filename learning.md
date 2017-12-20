---
layout: default
title: Learning
---
## [Learning]({{page.title}})
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
    {% if post.categories.first == "learning"  %}
      <li>
      <a href="{{ post.url }}"> {{ post.title }}</a> - {{ post.date | date: "%b %d, %Y"}}
      </li>
    {% endif %}
  {% endfor %}
  </ul>
</div>

