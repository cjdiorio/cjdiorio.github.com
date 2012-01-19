---
layout: page
title: Hello from cjdiorio 
header: cjdiorio
---


Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllboostrap.com)


    
## Posts



<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




