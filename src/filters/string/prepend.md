---
title: Prepend string filters
description: Adds the specified string to the beginning of another string.
liquidjs: https://liquidjs.com/filters/prepend.html
shopify: https://shopify.github.io/liquid/filters/prepend/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/prepend/
---
{{ "apples, oranges, and bananas" | prepend: "Some fruit: " }}  
{% assign url = "example.com" %}
{{ "/index.html" | prepend: url }}