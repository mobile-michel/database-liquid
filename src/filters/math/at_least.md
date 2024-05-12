---
title: at_least
description: Limits a number to a minimum value.
liquidjs: https://liquidjs.com/filters/at_least.html
shopify: https://shopify.github.io/liquid/filters/at_least/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/at_least/
---
### Example 1
input: {% raw %}
<code>
{{ 4 | at_least: 5 }}
</code>
{% endraw %}
output:
<code>
{{ 4 | at_least: 5 }}
</code>

### Example 2
input: {% raw %}
<code>
{{ 4 | at_least: 3 }}
</code>
{% endraw %}
output:
<code>
{{ 4 | at_least: 3 }}
</code>