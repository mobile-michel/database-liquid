---
title: Date filters
description: Converts a timestamp into another date format
list: format, timezone, input, current date
tags: filters
pagination:
    data: collections.date
    size: 10
    alias: items
---
{%- for post in items %}
- [{{ post.data.title }}]({{ post.url }}): {{ post.data.description }}
{%- endfor %}