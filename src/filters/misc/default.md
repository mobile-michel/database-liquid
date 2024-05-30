---
title: default
description: Allows you to specify a fallback in case a value doesn’t exist. default will show its value if the left side is falsy or empty (string or Array).
version: 1.9.1
works: true
---
{% assign formula = product_price | default: 2.99 %}
{% render 'example', number: 1, text: 'product_price | default: 2.99', code: formula %}

In this example, product_price is not defined, so the default value is used.  

### Example 2
input: {% raw %}
<code>
{% assign product_price = 4.99 %}  
{{ product_price | default: 2.99 }}
</code>
{% endraw %}
output:
<code>{% assign product_price = 4.99 %}{{ product_price | default: 2.99 }}</code>
  
In this example, product_price is defined, so the default value is not used.

### Example 3
input: {% raw %}
<code>
{% assign product_price = "" %}  
{{ product_price | default: 2.99 }}
</code>
{% endraw %}
output:
<code>{% assign product_price = "" %}{{ product_price | default: 2.99 }}</code>
  
In this example, product_price is empty, so the default value is used.

### Allowing false

Added in v9.32.0

To allow variables to return false instead of the default value, you can use the allow_false parameter:

input: {% raw %}
<code>
{% assign display_price = false %}
{{ display_price | default: true, allow_false: true }}
</code>
{% endraw %}
output:
<code>{% assign display_price = false %}{{ display_price | default: true, allow_false: true }}</code>