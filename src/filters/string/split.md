---
title: split
description: divides a string into an array using the argument as a separator. split is commonly used to convert comma-separated items from a string to an array.
version: 1.9.1
works: true
---
### Example
input: {% raw %}
<code>
{% assign beatles = "John, Paul, George, Ringo" | split: ", " %}  
{% for member in beatles %}  
  {{ member }}  
{% endfor %}
</code>
{% endraw %}
output:
<code>
{% assign beatles = "John, Paul, George, Ringo" | split: ", " %}  
{% for member in beatles %}  
  {{ member }}  
{% endfor %}
</code>