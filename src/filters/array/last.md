---
title: Last array filter
description: Returns the last item of an array.
liquidjs: https://liquidjs.com/filters/last.html
shopify: https://shopify.github.io/liquid/filters/last/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/last
---
{{ "Ground control to Major Tom." | split: " " | last }}  
{% assign my_array = "zebra, octopus, giraffe, tiger" | split: ", " %}
{{ my_array.last }}

You can use last with dot notation when you need to use the filter inside a tag:

{% if my_array.last == "tiger" %}
  There goes a tiger!
{% endif %}
