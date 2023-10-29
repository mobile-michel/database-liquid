---
title: Concat array filter
description: Concatenates (joins together) multiple arrays. The resulting array contains all the items from the input arrays.
liquidjs: https://liquidjs.com/filters/concat.html
shopify: https://shopify.github.io/liquid/filters/concat/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/concat
---
{% assign fruits = "apples, oranges, peaches" | split: ", " %}
{% assign vegetables = "carrots, turnips, potatoes" | split: ", " %}

{% assign everything = fruits | concat: vegetables %}

{% for item in everything %}
- {{ item }}
{% endfor %}

You can string together concat filters to join more than two arrays:

{% assign furniture = "chairs, tables, shelves" | split: ", " %}

{% assign everything = fruits | concat: vegetables | concat: furniture %}

{% for item in everything %}
- {{ item }}
{% endfor %}
