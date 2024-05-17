---
title: divided_by
description: divides a number by another number. The result is the string obtained by JavaScript .toString() of the result number.
version: 1.9.1
works: true
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