---
title: Truncate string filters
description: Shortens a string down to the number of characters passed as an argument. If the specified number of characters is less than the length of the string, an ellipsis (…) is appended to the string and is included in the character count.
liquidjs: https://liquidjs.com/filters/truncate.html
shopify: https://shopify.github.io/liquid/filters/truncate/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/truncate
---
{{ "Ground control to Major Tom." | truncate: 20 }}