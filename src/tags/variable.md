---
title: Variable tags
description: define and alter variables (assign, increment, decrement, capture, echo)
tags: tags
pagination:
    data: collections.variable
    size: 10
    alias: items
---
{%- for post in items %}
- [{{ post.data.title }}]({{ post.url }}): {{ post.data.description }}
{%- endfor %}