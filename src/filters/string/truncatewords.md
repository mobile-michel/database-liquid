---
title: Truncatewords string filters
description: Shortens a string down to the number of words passed as an argument. If the specified number of words is less than the number of words in the string, an ellipsis (…) is appended to the string.
liquidjs: https://liquidjs.com/filters/truncatewords.html
shopify: https://shopify.github.io/liquid/filters/truncatewords/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/truncatewords
---
{{ "Ground control to Major Tom." | truncatewords: 3 }}