---
layout: default
title: writing
---
## [Writing]({{page.url}})
<div class="postcontent archive">
  <ul class="archive">
  {% for post in site.posts %}
      {% unless post.categories contains "diary"  %}
      {% unless post.categories contains "draft"  %}
       {% unless post.categories contains "others" %}
        {% unless post.categories contains "language" %}
      <li>
      <a href="{{ post.url }}"> {{ post.title }}</a>
      <span class="archivedate hidemobile">{{ post.date | date: "%b %d, %Y"}}</span>
      </li>
         {% endunless %}
       {% endunless %}
    {% endunless %}
    {% endunless %}
  {% endfor %}
  </ul>
</div>
