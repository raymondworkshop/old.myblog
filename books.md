---
layout: post
title: Courses
---
####Courses Ongoing
   * Algorithms
       -  [Computability, Complexity & Algorithms on Udacity] (https://www.udacity.com/wiki/ud061)
       -  [Algorithms, Part I] (https://www.coursera.org/course/algs4partI)

   * System
       -  [Computer Systems: A Programmer's Perspective] (http://cs61.seas.harvard.edu/wiki/2015/Home)
       -  [Advanced Operating Systems on Udacity] (https://www.udacity.com/wiki/ud189) 


   * English learning
       -  [Writing in the Sciences] (https://lagunita.stanford.edu/dashboard)


   *  Cantonese learning 
  
#### books
<div class="postcontent archive">
  <ul class="archive">
  {% for post in site.posts %}
    {% if post.categories.first == "books"  %}
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