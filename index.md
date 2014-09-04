---
layout: page
title: Welcome!
---
{% include JB/setup %}
## Recent posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>





This blog is still a newborn. 

Recent posts will be posted here, so expect greatness.

Check out the 'About Me' for a short introduction. 




<!-- ## To-Do

<ul>
<li>Make my blog debut! Will be in place of "Touching Base"
</ul>


-->