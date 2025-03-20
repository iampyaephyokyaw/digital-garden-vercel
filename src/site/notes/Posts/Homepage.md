---
{"dg-publish":true,"permalink":"/Posts/Homepage/","title":"Welcome to My Digital Garden","tags":["gardenEntry"]}
---

# Welcome to My Digital Garden

Hi there! I'm Pyae Phyo Kyaw, and this is my digital garden, a place where I cultivate my thoughts and share my knowledge.

Latest notes

{% for post in collections.posts | reverse | limit(5) %}
- [{{ post.data.title }}]({{ post.url }}) - {{ post.date | date: "yyyy-MM-dd" }}
{% endfor %}

## About Me

[This is who I am ok]