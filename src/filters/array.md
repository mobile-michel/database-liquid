---
title: Array filters
description: Array filters modify arrays.
list: slice, map, sort, sort_natural, uniq, where, first, last, join, reverse, concat, compact, size
tags: filters
pagination:
    data: collections.array
    size: 100
    alias: items
---
{%- for post in items %}
- [{{ post.data.title }}]({{ post.url }}): {{ post.data.description }}
{%- endfor %}