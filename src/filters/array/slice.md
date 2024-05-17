---
title: slice
description: Returns a substring of 1 character beginning at the index specified by the first argument. An optional second argument specifies the length of the substring to be returned. String indices are numbered starting from 0.
liquidjs: https://liquidjs.com/filters/slice.html
shopify: https://shopify.github.io/liquid/filters/slice/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/slice
---
### Example 1
input: {% raw %}
<code>
{{ "Liquid" | slice: 0 }}
</code>
{% endraw %}
output:
<code>
{{ "Liquid" | slice: 0 }}
</code>
### Example 2
input: {% raw %}
<code>
{{ "Liquid" | slice: 2 }}
</code>
{% endraw %}
output:
<code>
{{ "Liquid" | slice: 2 }}
</code>
### Example 3
input: {% raw %}
<code>
{{ "Liquid" | slice: 2, 5 }}
</code>
{% endraw %}
output:
<code>
{{ "Liquid" | slice: 2, 5 }}
</code>
### Example 4
input: {% raw %}
<code>
{{ "Liquid" | slice: -3, 2 }}
</code>
{% endraw %}
output:
<code>
{{ "Liquid" | slice: -3, 2 }}
</code>