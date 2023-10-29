---
title: Sort_natural array filter
description: Sorts items in an array in case-insensitive order.
liquidjs: https://liquidjs.com/filters/sort_natural.html
shopify: https://shopify.github.io/liquid/filters/sort_natural/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/sort_natural
---
{% assign my_array = "zebra, octopus, giraffe, Sally Snake" | split: ", " %}
{{ my_array | sort_natural | join: ", " }}  
{% assign products_by_company = collection.products | sort_natural: "company" %}
{% for product in products_by_company %}
  <h4>{{ product.title }}</h4>
{% endfor %}