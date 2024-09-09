---
title: All elements
description: list of filters in LiquidJS.
date: 2024-01-01
layout: default
tags: primary
pagination:
  data: liquid
  size: 30

---
{%- for item in pagination.items %}
- **{{ item.category | capitalize }}**: {{ item.categoryDescription }}
{% endfor -%}