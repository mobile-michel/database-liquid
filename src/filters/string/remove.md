---
title: remove
description: removes every occurrence of the specified substring from a string.
version: 1.9.1
works: true
---
### Example 1
input: {% raw %}
<code>
{{ "I strained to see the train through the rain" | remove: "rain" }}
</code>
{% endraw %}
output:
<code>
{{ "I strained to see the train through the rain" | remove: "rain" }}
</code>