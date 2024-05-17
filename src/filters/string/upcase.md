---
title: upcase
description: makes each character in a string uppercase. It has no effect on strings which are already all uppercase.
version: 1.9.1
works: true
---
### Example 1
input: {% raw %}
<code>
{{ "Parker Moore" | upcase }}
</code>
{% endraw %}
output:
<code>
{{ "Parker Moore" | upcase }}
</code>
### Example 2
input: {% raw %}
<code>
{{ "APPLE" | upcase }}
</code>
{% endraw %}
output:
<code>
{{ "APPLE" | upcase }}
</code>