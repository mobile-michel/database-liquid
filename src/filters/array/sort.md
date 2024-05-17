---
title: sort
description: Sorts items in an array in case-sensitive order.
liquidjs: https://liquidjs.com/filters/sort.html
shopify: https://shopify.github.io/liquid/filters/sort/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/sort
---
### Example 1
input: {% raw %}
<code>
{% assign my_array = "zebra, octopus, giraffe, Sally Snake" | split: ", " %}  
{{ my_array | sort | join: ", " }}
</code>
{% endraw %}
output:
<code>{% assign my_array = "zebra, octopus, giraffe, Sally Snake" | split: ", " %}
{{ my_array | sort | join: ", " }}
</code>

### Example 2
An optional argument specifies which property of the array’s items to use for sorting:  
input: {% raw %}
<code>{% assign products_by_price = collection.products | sort: "price" %}  
{% for product in products_by_price %}  
  {{ product.title }}  
{% endfor %}
</code>
{% endraw %}
output:
<code>{% assign products_by_price = products.collection.products | sort: "price" %}
{% for product in products_by_price %}
  - {{ product.title }} is {{ product.price }}$
{% endfor %}
</code>