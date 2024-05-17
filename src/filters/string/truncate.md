---
title: truncate
description: shortens a string down to the number of characters passed as an argument. If the specified number of characters is less than the length of the string, an ellipsis (…) is appended to the string and is included in the character count.
version: 1.9.1
works: true
---
### Basic usage
input: {% raw %}
<code>
{{ "Ground control to Major Tom." | truncate: 20 }}
</code>
{% endraw %}
output:
<code>
{{ "Ground control to Major Tom." | truncate: 20 }}
</code>
### Custom ellipsis
input: {% raw %}
<code>
{{ "Ground control to Major Tom." | truncate: 25, ", and so on" }}
</code>
{% endraw %}
output:
<code>
{{ "Ground control to Major Tom." | truncate: 25, ", and so on" }}
</code>
### No ellipsis
input: {% raw %}
<code>
{{ "Ground control to Major Tom." | truncate: 20, "" }}
</code>
{% endraw %}
output:
<code>
{{ "Ground control to Major Tom." | truncate: 20, "" }}
</code>