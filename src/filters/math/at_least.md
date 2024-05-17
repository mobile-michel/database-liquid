---
title: at_least
description: limits a number to a minimum value.
version: 8.4.0
works: true
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