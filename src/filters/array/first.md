---
title: First array filter
description: Returns the first item of an array.
liquidjs: https://liquidjs.com/filters/first.html
shopify: https://shopify.github.io/liquid/filters/first/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/first
---
{{ "Ground control to Major Tom." | split: " " | first }}  
{% assign my_array = "zebra, octopus, giraffe, tiger" | split: ", " %}
{{ my_array.first }}  

You can use first with dot notation when you need to use the filter inside a tag:

{% if my_array.first == "zebra" %}
  Here comes a zebra!
{% endif %}