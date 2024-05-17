---
title: append
description: concatenates two strings and returns the concatenated value.
version: 1.9.1
works: true
---
### Example 1
input: {% raw %}
<code>
{{ "/my/fancy/url" | append: ".html" }}
</code>
{% endraw %}
output:
<code>
{{ "/my/fancy/url" | append: ".html" }}
</code>
### Example 2
input: {% raw %}
<code>
{% assign filename = "/index.html" %}  
{{ "website.com" | append: filename }}
</code>
{% endraw %}
output:
<code>{% assign filename = "/index.html" %}
{{ "website.com" | append: filename }}
</code>