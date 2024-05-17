---
title: normalize_whitespace
description: replace any occurrence of whitespace with a single space.
version: 10.13.0
works: false
---
### Example
input: {% raw %}
<code>
{{ "a \n b" | normalize_whitespace }}
</code>
{% endraw %}
output:
<code>
! This filter is not working yet !  
output should be: a b
</code>
