---
title: floor
description: rounds the input down to the nearest whole number. LiquidJS tries to convert the input to a number before the filter is applied.
version: 1.9.1
works: true
---
### Example 1
input: {% raw %}
<code>
{{ 1.2 | floor }}
</code>
{% endraw %}
output:
<code>
{{ 1.2 | floor }}
</code>

### Example 2
input: {% raw %}
<code>
{{ 2.0 | floor }}
</code>
{% endraw %}
output:
<code>
{{ 2.0 | floor }}
</code>

### Example 3
input: {% raw %}
<code>
{{ 183.357 | floor }}
</code>
{% endraw %}
output:
<code>
{{ 183.357 | floor }}
</code>

### Example 4
input: {% raw %}
<code>
{{ "3.5" | floor }}
</code>
{% endraw %}
output:
<code>
{{ "3.5" | floor }}
</code>