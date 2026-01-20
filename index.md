---
layout: brain 
title: Brainfuck nu
---


## For the love of?

Brainfuck is a brilliant language to melt your brain. 
Read the description on [Brian Raiters page](http://www.muppetlabs.com/~breadbox/bf/)

## Blog Posts

{% for post in site.posts %}
  * [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}


