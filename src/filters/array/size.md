---
title: Size array filter
description: Returns the number of characters in a string or the number of items in an array.
liquidjs: https://liquidjs.com/filters/size.html
shopify: https://shopify.github.io/liquid/filters/size/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/size
---
{{ "Ground control to Major Tom." | size }}

{% assign my_array = "apples, oranges, peaches, plums" | split: ", " %}
{{ my_array.size }}

{% if site.pages.size > 6 %}
  This is a big website!
{% endif %}