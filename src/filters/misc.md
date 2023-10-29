---
title: Miscellanous filters
description: 
list: default, json, raw
layout: base
tags: filters
pagination:
    data: collections.misc
    size: 10
    alias: items
---
{%- for post in items %}
- [{{ post.data.title }}]({{ post.url }}): {{ post.data.description }}
{%- endfor %}