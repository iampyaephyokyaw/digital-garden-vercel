---
{"dg-publish":true,"permalink":"/Posts/Homepage/","title":"Welcome to My Digital Garden","tags":["gardenEntry"]}
---

# Welcome to My Digital Garden

Hi there! I'm Pyae Phyo Kyaw, and this is my digital garden, a place where I cultivate my thoughts and share my knowledge.

Latest notes

{% for notes in site.notes limit:5 %}
-  {{ note.date | date: "%Y-%m-%d" }} - [{{ note.title }}]({{ note.url }})
{% endfor %}

## About Me

[This is who I am ok]