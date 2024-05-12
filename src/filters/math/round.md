---
title: round
description: Rounds a number to the nearest integer or, if a number is passed as an argument, to that number of decimal places.
liquidjs: https://liquidjs.com/filters/round.html
shopify: https://shopify.github.io/liquid/filters/round/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/round
---
### Example 1
input: {% raw %}
<code>
{{ 1.2 | round }}
</code>
{% endraw %}
output:
<code>
{{ 1.2 | round }}
</code>

### Example 2
input: {% raw %}
<code>
{{ 2.7 | round }}
</code>
{% endraw %}
output:
<code>
{{ 2.7 | round }}
</code>

### Example 3
input: {% raw %}
<code>
{{ 183.357 | round }}
</code>
{% endraw %}
output:
<code>
{{ 183.357 | round }}
</code>