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





Recent posts will be posted here, so expect greatness!

Check out the 'About Me' for a short introduction. 




<!-- ## To-Do

	Fix the issues with the mobile version 
		- Will not zoom out
		- Text does not wrap into phone screen
		- Pictures inserted without js will 


-->