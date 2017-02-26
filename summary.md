---
layout: default
title: Summary
---
## [Summary]({{page.url}})
<div class="postcontent archive">
  <ul class="archive">
  {% for post in site.posts %}
    {% if post.categories.first == "summary"  %}
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