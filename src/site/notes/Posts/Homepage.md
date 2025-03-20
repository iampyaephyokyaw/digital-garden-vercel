---
{"dg-publish":true,"permalink":"/posts/homepage/","title":"Welcome to My Digital Garden","tags":["gardenEntry"]}
---

# Welcome to My Digital Garden

Hi there! I'm Pyae Phyo Kyaw, and this is my digital garden, a place where I cultivate my thoughts and share my knowledge.

## Latest posts

{% for posts in site.posts limit:5 %}
- {{ post.date | date: "%Y-%m-%d" }} - [{{ post.title }}]({{ post.url }})
{% endfor %}

## About Me

[This is who I am]