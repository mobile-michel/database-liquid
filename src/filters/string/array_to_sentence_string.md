---
title: array_to_sentence_string
description: convert an array into a sentence. Useful for listing tags. Optional argument for connector.
version: 10.13.0
works: false
---
### Example 1
input: {% raw %}
<code>
{{ "foo,bar,baz" | split: "," | array_to_sentence_string }}
</code>
{% endraw %}
output:
<code>
! This filter is not working yet !  
output should be: foo, bar, and baz
</code>
### Example 2
input: {% raw %}
<code>
{{ "foo,bar,baz" | split: "," | array_to_sentence_string: "or" }}
</code>
{% endraw %}
output:
<code>
! This filter is not working yet !  
output should be: foo, bar, or baz
</code>