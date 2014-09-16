---
layout: page
title: Welcome!
---
{% include JB/setup %}

Welcome to my lifestyle blog! I write about technology, internet drama, music, and events. Take your time here. 

Check out the 'About Me' for a short introduction. 


## Recent posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


I'm a little backed up due to a busy lifestyle. Forgive me!

Four posts (and one series) to look forward to:
<ol><li>Jury Duty and the domingating demographic of each crime</li>
<li>Champions of the Coast [rhythm game tournament] weekend.</li>
<li>Project: GameCube to 3DS converter</li>
<li>Series: How do lasers work?</li>
</ol>

<!-- ## To-Do

	Fix the issues with the mobile version 
		- Will not zoom out
		- Text does not wrap into phone screen
		- Pictures inserted without js will 


-->