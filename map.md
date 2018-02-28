---
layout: page
title: Novice
published: true
---


<div class="posts" style="padding-bottom: 40px;">


  {% for post in site.posts %}


    <span class="post-date" style="display:inline-block; width:60px; margin:auto; padding:0; font-size:10px;">{{ post.date | date: "%-d. %-m. %Y" }}</span>

   <!-- <span class="post-date" style="display:inline-block; width:60px; margin:auto; padding:0; font-size:10px;">{{ post.date | date_to_string }}</span>  -->
   <a href="{{ site.url }}{{ post.url }}"/> {{ post.title }} </a>

   <br>
   
  {% endfor %}
  
</div>

