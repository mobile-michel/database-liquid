---
title: strip_newlines
description: removes any newline characters (line breaks) from a string.
version: 1.9.1
works: true
---
### Example
input: {% raw %}
<code>{% capture string_with_newlines %}  
Hello  
there  
{% endcapture %}  
{{ string_with_newlines | strip_newlines }}
</code>
{% endraw %}
output:
<code>{% capture string_with_newlines %}
Hello
there
{% endcapture %}
{{ string_with_newlines | strip_newlines }}
</code>