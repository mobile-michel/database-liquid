---
title: sort_natural
description: Sorts items in an array in case-insensitive order.
version: 8.4.0
works: true
---
### Example 1
input: {% raw %}
<code>
{% assign my_array = "zebra, octopus, giraffe, Sally Snake" | split: ", " %}  
{{ my_array | sort_natural | join: ", " }}
</code>
{% endraw %}
output:
<code>{% assign my_array = "zebra, octopus, giraffe, Sally Snake" | split: ", " %}
{{ my_array | sort_natural | join: ", " }}
</code>
### Example 2
input: {% raw %}
<code>
{% assign products_by_company = products.collection.products | sort_natural: "vendor" %}  
{% for product in products_by_company %}  
{{ product.title }}  
{% endfor %}
</code>
{% endraw %}
output:
<code>{% assign products_by_company = products.collection.products | sort_natural: "vendor" %}
{% for product in products_by_company %}
- {{ product.title }} ({{ product.vendor }})
{% endfor %}
</code>