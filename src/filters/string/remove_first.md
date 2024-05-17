---
title: remove_first
description: removes only the first occurrence of the specified substring from a string.
version: 1.9.1
works: true
---
### Example 1
input: {% raw %}
<code>
{{ "I strained to see the train through the rain" | remove_first: "rain" }}
</code>
{% endraw %}
output:
<code>
{{ "I strained to see the train through the rain" | remove_first: "rain" }}
</code>