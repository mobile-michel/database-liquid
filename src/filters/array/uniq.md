---
title: Uniq array filter
description: Removes any duplicate elements in an array.
liquidjs: https://liquidjs.com/filters/uniq.html
shopify: https://shopify.github.io/liquid/filters/uniq/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/uniq
---
### Example 1
input: {% raw %}
<code>
{% assign my_array = "ants, bugs, bees, bugs, ants" | split: ", " %}  
{{ my_array | uniq | join: ", " }}
</code>
{% endraw %}
output:
<code>{% assign my_array = "ants, bugs, bees, bugs, ants" | split: ", " %}
{{ my_array | uniq | join: ", " }}
</code>