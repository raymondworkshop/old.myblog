---
layout: default
title: Writing
---
 
#### Nov 24, 2019 [I give a presentation about Japan in views of culture](https://drive.google.com/open?id=1pxve4i0LEUI8Vyv14BEAUQD_2UsKusw74gt32sZRxso)  
You can contact with me for the details. Or you can tell me some country/region you are interested in, I might share some insights about it with you.  
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
