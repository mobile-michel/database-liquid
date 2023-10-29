---
title: Language tags
description: temporarily disable LiquidJS syntax (# inline comment, raw, comment, liquid)
tags: tags
pagination:
    data: collections.language
    size: 10
    alias: items
---
{%- for post in items %}
- [{{ post.data.title }}]({{ post.url }}): {{ post.data.description }}
{%- endfor %}