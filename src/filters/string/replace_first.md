---
title: replace_first
description: replaces only the first occurrence of the first argument in a string with the second argument.
version: 1.9.1
works: true
---
### Example
input: {% raw %}
<code>
{{ "Take my protein pills and put my helmet on" | replace_first: "my", "your" }}
</code>
{% endraw %}
output:
<code>
{{ "Take my protein pills and put my helmet on" | replace_first: "my", "your" }}
</code>