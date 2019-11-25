---
layout: default
title: Writing
---
 
#### Nov 24, 2019 I give a presentation about [Japan in views of culture](https://drive.google.com/open?id=1pxve4i0LEUI8Vyv14BEAUQD_2UsKusw74gt32sZRxso).  
 
<br/>

<div >
  <ul class="posts">
  {% for post in site.posts %}
    {% if post.categories contains 'writing'  %}
      <li>
      
      <small>{{ post.date | date: "%b %d, %Y"}}</small> <br>
      <a href="{{ post.url }}"> {{ post.title }}</a>  <br>   
          {{ post.abstract }} <br>
      
      </li>

    {% endif %}
  {% endfor %}
  </ul>
</div>
