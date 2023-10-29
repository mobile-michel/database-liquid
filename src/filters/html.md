---
title: HTML/URI filters
description: 
list: escape, escape_once, url_encode, url_decode, strip_html, newline_to_br
tags: filters
pagination:
    data: collections.html
    size: 10
    alias: items
---
{%- for post in items %}
- [{{ post.data.title }}]({{ post.url }}): {{ post.data.description }}
{%- endfor %}