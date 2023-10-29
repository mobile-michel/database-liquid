---
title: Iteration tags
description: Iterate over a collection (for, cycle, tablerow)
tags: tags
pagination:
    data: collections.iteration
    size: 10
    alias: items
---
{%- for post in items %}
- [{{ post.data.title }}]({{ post.url }}): {{ post.data.description }}
{%- endfor %}