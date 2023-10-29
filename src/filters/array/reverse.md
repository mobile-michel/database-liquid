---
title: Reverse array filter
description: Reverses the order of the items in an array. Reverse cannot reverse a string.
liquidjs: https://liquidjs.com/filters/reverse.html
shopify: https://shopify.github.io/liquid/filters/reverse/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/reverse
---
{% assign my_array = "apples, oranges, peaches, plums" | split: ", " %}

{{ my_array | reverse | join: ", " }}

Although reverse cannot be used directly on a string, you can split a string into an array, reverse the array, and rejoin it by chaining together filters:

{{ "Ground control to Major Tom." | split: "" | reverse | join: "" }}