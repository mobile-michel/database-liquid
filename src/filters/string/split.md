---
title: Split string filters
description: Divides a string into an array using the argument as a separator. split is commonly used to convert comma-separated items from a string to an array.
liquidjs: https://liquidjs.com/filters/split.html
shopify: https://shopify.github.io/liquid/filters/split/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/split
---
{% assign beatles = "John, Paul, George, Ringo" | split: ", " %}

{% for member in beatles %}
  {{ member }}
{% endfor %}