---
title: Marwan's Tutorial Blog
---

## Marwan's Tutorial Blog

This is my new blog, the main purpose is to publish tutorial or quick coding
stuff.

I'll probably present posts related to programming under Linux or other Unix
env, C or C++ programming, parallel programming, algorithms …

{% for post in site.posts %}
* {{ post.date | date_to_string }} [{{ post.title }}]({{ post.url }})
{% endfor %}
