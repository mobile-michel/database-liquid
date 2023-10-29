---
title: Join array filter
description: Combines the items in an array into a single string using the argument as a separator.
liquidjs: https://liquidjs.com/filters/join.html
shopify: https://shopify.github.io/liquid/filters/join/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/join
---
{% assign beatles = "John, Paul, George, Ringo" | split: ", " %}
{{ beatles | join: " and " }}