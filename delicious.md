---
layout: default
title: Delicious
---
## [Delicious]({{page.title}})

<ul class="archive">
        {% delicious username:muyun tag:todo tag:toread tag:education tag:life count:20 ttl:3600 %}
        <li><a href="{{ item.link }}" title="{{ item.description }}" rel="external">{{ item.title }}</a></li>
        {% enddelicious %}
</ul>

