---
title: round
description: rounds a number to the nearest integer or, if a number is passed as an argument, to that number of decimal places.
version: 1.9.1
works: true
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