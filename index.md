---
layout: page
title: John Lee's Hacker BLOG ACTION
tagline: The entry
---
{% include JB/setup %}

Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

## ALL ABOUT ME

I will still need to understand custom config in the '_config.yml' file but... thats for another day
    
    title : The pillar of fire
    
    author :
      name : John Lee Super Hacker
      email : Done_Deal@donedeal.com
      github : TheExodus


The theme should reference these variables whenever needed.
    
## Thus begins the blog posts...

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

To create my own theme or not to... lets try it.


