---
title: Escape_once HTML/URI filters
description: Escapes a string without changing existing escaped entities. It doesn’t change strings that don’t have anything to escape.
liquidjs: https://liquidjs.com/filters/escape_once.html
shopify: https://shopify.github.io/liquid/filters/escape_once/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/escape_once
---
{{ "1 < 2 & 3" | escape_once }}  
{{ "1 &lt; 2 &amp; 3" | escape_once }}