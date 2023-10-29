---
title: Strip_newlines string filters
description: Removes any newline characters (line breaks) from a string.
liquidjs: https://liquidjs.com/filters/strip_newlines.html
shopify: https://shopify.github.io/liquid/filters/strip_newlines/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/strip_newlines
---
{% capture string_with_newlines %}
Hello
there
{% endcapture %}

{{ string_with_newlines | strip_newlines }}