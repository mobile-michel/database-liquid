---
title: divided_by
description: Divides a number by another number. The result is the string obtained by JavaScript .toString() of the result number.
liquidjs: https://liquidjs.com/filters/divided_by.html
shopify: https://shopify.github.io/liquid/filters/divided_by/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/divided_by/
---
### Example 1
input: {% raw %}
<code>
{{ 16 | divided_by: 4 }}
</code>
{% endraw %}
output:
<code>
{{ 16 | divided_by: 4 }}
</code>

### Example 2
input: {% raw %}
<code>
{{ 5 | divided_by: 3 }}
</code>
{% endraw %}
output:
<code>
{{ 5 | divided_by: 3 }}
</code>

### Example 3
input: {% raw %}
<code>
{{ 5 | divided_by: 3, true }}
</code>
{% endraw %}
output:
<code>
{{ 5 | divided_by: 3, true }}
</code>