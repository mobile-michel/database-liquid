---
title: File tags
description: include another template or extend a layout template (render, include, layout)
tags: tags
pagination:
    data: collections.file
    size: 10
    alias: items
---
{%- for post in items %}
- [{{ post.data.title }}]({{ post.url }}): {{ post.data.description }}
{%- endfor %}