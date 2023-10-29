---
title: Math filters
description: Math filters perform mathematical operations on numbers. You can apply math filters to numbers, or variables or metafields that return a number. As with any other filters, you can use multiple math filters on a single input. They’re applied from left to right.
list: plus, minus, modulo, times, floor, ceil, round, divided_by, abs, at_least, at_most
tags: filters
pagination:
    data: collections.math
    size: 100
    alias: items
---
{%- for post in items %}
- [{{ post.data.title }}]({{ post.url }}): {{ post.data.description }}
{%- endfor %}