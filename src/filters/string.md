---
title: String filters
description: String filters modify strings.
list: append, prepend, capitalize, upcase, downcase, strip, lstrip, rstrip, strip_newlines, split, replace, replace_first, replace_last,remove, remove_first, remove_last, truncate, truncatewords
tags: filters
pagination:
    data: collections.string
    size: 100
    alias: items
---
{%- for post in items %}
- [{{ post.data.title }}]({{ post.url }}): {{ post.data.description }}
{%- endfor %}