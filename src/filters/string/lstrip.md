---
title: lstrip
description: removes all whitespace (tabs, spaces, and newlines) from the left side of a string. It does not affect spaces between words.
version: 1.9.1
works: true
---
### Example
input: {% raw %}
<code>
BEGIN{{ "          So much room for activities!          " | lstrip }}END
</code>
{% endraw %}
output:
<code>
BEGIN{{ "          So much room for activities!          " | lstrip }}END
</code>