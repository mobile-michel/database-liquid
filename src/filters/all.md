---
title: All filters
description: 
list: Math, string, HTML, array, date & misc filters
tags: filters
pagination:
    data: collections.allFilters
    size: 100
    alias: items
---
{%- for post in items %}
- [{{ post.data.title }}]({{ post.url }}): {{ post.data.description }}
{%- endfor %}