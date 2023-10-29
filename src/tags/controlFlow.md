---
title: Control flow tags
description: control the execution branch of template rendering (if, unless, elsif, else, case, when)
tags: tags
pagination:
    data: collections.controlFlow
    size: 10
    alias: items
---
{%- for post in items %}
- [{{ post.data.title }}]({{ post.url }}): {{ post.data.description }}
{%- endfor %}