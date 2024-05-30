---
title: Filters v2
description: list of filters in LiquidJS.
date: 2024-01-01
layout: default
tags: primary
pagination:
  data: liquid
  size: 30
---
{% assign items = liquid %}
{%- for item in items %}
- [{{ item.data.title }}]({{ item.url }}): {{ item.data.description }}
**List of {{ item.data.title }}**: {{ item.data.list }}
{%- endfor %}