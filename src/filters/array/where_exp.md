---
title: where_exp
description: Creates an array including only the objects with a given property value, or any truthy value by default. In this example, assume you have a list of products and you want to show your kitchen products separately. Using where, you can create an array containing only the products that have a "type" of "kitchen".
liquidjs: https://liquidjs.com/filters/where.html
shopify: https://shopify.github.io/liquid/filters/where/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/where
---
{% assign polina_products = products.collection.products | where: 'vendor', "Polina's Potent Potions" %}

Products from Polina's Potent Potions:

{% for product in polina_products %}
  - {{ product.title }}
{%- endfor %}

All products:
{% for product in products.collection.products %}
- {{ product.title }}
{%- endfor %}

{% assign kitchen_products = products.collection.products | where_exp: "item", "item.vendor == 'Polinas Potent Potions'" %}

Kitchen products:
{% for product in kitchen_products %}
- {{ product.title }}
{% endfor %}