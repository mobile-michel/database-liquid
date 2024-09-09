---
title: filters
description: list of filters in LiquidJS.
date: 2024-01-02
layout: default
tags: primary
pagination:
  data: liquid
  size: 30

---
{% assign items = pagination.items %}
{%- for item in items %}
- **{{ item }}**
{% endfor -%}