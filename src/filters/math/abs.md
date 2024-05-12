---
title: abs
description: Liquid filter that returns the absolute value of a number.
liquidjs: https://liquidjs.com/filters/abs.html
shopify: https://shopify.github.io/liquid/filters/abs/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/abs
---
### Example 1
input: {% raw %}
<code>
{{ -17 | abs }}
</code>
{% endraw %}
output:
<code>
{{ -17 | abs }}
</code>

### Example 2
input: {% raw %}
<code>
{{ 4 | abs }}
</code>
{% endraw %}
output:
<code>
{{ 4 | abs }}
</code>

### Example 3
input: {% raw %}
<code>
{{ "-19.86" | abs }}
</code>
{% endraw %}
output:
<code>
{{ "-19.86" | abs }}
</code>