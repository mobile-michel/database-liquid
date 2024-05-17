---
title: remove_last
description: removes only the last occurrence of the specified substring from a string.
version: 10.2.0
works: true
---
### Example 1
input: {% raw %}
<code>
{{ "I strained to see the train through the rain" | remove_last: "rain" }}
</code>
{% endraw %}
output:
<code>
{{ "I strained to see the train through the rain" | remove_last: "rain" }}
</code>