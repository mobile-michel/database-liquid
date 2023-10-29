---
title: Filters
description: Filters change the output of a Liquid object or variable. They are used within double curly braces {{ }} and variable assignment, and are separated by a pipe character |. Multiple filters can be used on one output, and are applied from left to right.
tags: primary
pagination:
    data: collections.filters
    size: 10
    alias: items
---
{%- for post in items %}
- [{{ post.data.title }}]({{ post.url }}): {{ post.data.description }}  
**List of {{ post.data.title }}**: {{ post.data.list }}
{%- endfor %}