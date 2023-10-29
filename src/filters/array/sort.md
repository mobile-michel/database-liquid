---
title: Sort array filter
description: Sorts items in an array in case-sensitive order.
liquidjs: https://liquidjs.com/filters/sort.html
shopify: https://shopify.github.io/liquid/filters/sort/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/sort
---
{% assign my_array = "zebra, octopus, giraffe, Sally Snake" | split: ", " %}
{{ my_array | sort | join: ", " }}  
{% assign products_by_price = collection.products | sort: "price" %}
{% for product in products_by_price %}
  <h4>{{ product.title }}</h4>
{% endfor %}