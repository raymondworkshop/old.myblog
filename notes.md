---
layout: post
title: notes
--- 
#### book notes
<div class="postcontent archive">
  <ul class="archive">
  {% for post in site.posts %}
    {% if post.categories.first == "notes"  %}
      <li>
      <a href="{{ post.url }}"> {{ post.title }}</a>

      <span class="archivedate hidemobile">{{ post.date | date: "%b %d, %Y"}}</span>

      </li>
    {% endif %}
  {% endfor %}
  </ul>
</div>

