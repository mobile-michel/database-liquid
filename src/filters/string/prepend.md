---
title: prepend
description: adds the specified string to the beginning of another string.
version: 1.9.1
works: true
---
### Example 1
input: {% raw %}
<code>
{{ "apples, oranges, and bananas" | prepend: "Some fruit: " }}
</code>
{% endraw %}
output:
<code>
{{ "apples, oranges, and bananas" | prepend: "Some fruit: " }}
</code>
### Example 2
input: {% raw %}
<code>
{% assign url = "example.com" %}  
{{ "/index.html" | prepend: url }}
</code>
{% endraw %}
output:
<code>{% assign url = "example.com" %}
{{ "/index.html" | prepend: url }}
</code>