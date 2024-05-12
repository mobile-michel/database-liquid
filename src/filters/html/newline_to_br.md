---
title: Newline_to_br HTML/URI filters
description: Replaces every newline (\n) in a string with an HTML line break (<br />).
liquidjs: https://liquidjs.com/filters/newline_to_br.html
shopify: https://shopify.github.io/liquid/filters/newline_to_br/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/newline_to_br
---
{% capture string_with_newlines %}
Hello
there
{% endcapture %}

{{ string_with_newlines | newline_to_br }}