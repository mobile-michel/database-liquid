---
title: Escape HTML/URI filters
description: Escapes a string by replacing HTML special characters with escape sequences. It doesn’t change strings that don’t have anything to escape.
liquidjs: https://liquidjs.com/filters/escape.html
shopify: https://shopify.github.io/liquid/filters/escape/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/escape
---
{{ "Have you read 'James & the Giant Peach'?" | escape }}  
{{ "Tetsuro Takara" | escape }}