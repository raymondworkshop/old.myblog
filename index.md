---
layout: default
title: writing
---
## [Notes]({{page.url}})
<div class="postcontent archive">
  <ul class="archive">
  {% for post in site.posts %}
      {% unless post.categories contains "diary"  %}
      {% unless post.categories contains "draft"  %}
       {% unless post.categories contains "others" %}
      <li>
      <small>{{ post.date | date: "%b %d, %Y"}}</small> <br>
      <a href="{{ post.url }}"> {{ post.title }}</a>  <br>   
          {{ post.abstract }}  <br>
          <br>

      <!--
      <span class="archivedate hidemobile">{{ post.date | date: "%b %d, %Y"}}</span>
      -->
      </li>
       {% endunless %}
    {% endunless %}
    {% endunless %}
  {% endfor %}
  </ul>
</div>
