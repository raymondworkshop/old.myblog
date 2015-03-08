---
layout: default
title: writing
---
## [Writing]({{page.url}})
<div class="postcontent archive">
  <ul class="archive">
  {% for post in site.posts %}
    {% unless post.categories.first == "_drafts"  %}
      {% unless post.categories.first == "diary"  %}
      <li>
      <a href="{{ post.url }}"> {{ post.title }}</a>
      <span class="archivedate hidemobile">{{ post.date | date: "%b %d, %Y"}}</span>
      </li>
      {% endunless %}
    {% endunless %}
  {% endfor %}
  </ul>
</div>
