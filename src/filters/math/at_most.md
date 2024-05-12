---
title: at_most
description: Limits a number to a maximum value.
liquidjs: https://liquidjs.com/filters/at_most.html
shopify: https://shopify.github.io/liquid/filters/at_most/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/at_most/
---
### Example 1
input: {% raw %}
<code>
{{ 4 | at_most: 5 }}
</code>
{% endraw %}
output:
<code>
{{ 4 | at_most: 5 }}
</code>

### Example 2
input: {% raw %}
<code>
{{ 4 | at_most: 3 }}
</code>
{% endraw %}
output:
<code>
{{ 4 | at_most: 3 }}
</code>