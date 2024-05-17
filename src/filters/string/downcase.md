---
title: downcase
description: makes each character in a string lowercase. It has no effect on strings which are already all lowercase.
version: 1.9.1
works: true
---
### Example 1
input: {% raw %}
<code>
{{ "Parker Moore" | downcase }}
</code>
{% endraw %}
output:
<code>
{{ "Parker Moore" | downcase }}
</code>
### Example 2
input: {% raw %}
<code>
{{ "apple" | downcase }}
</code>
{% endraw %}
output:
<code>
{{ "apple" | downcase }}
</code>