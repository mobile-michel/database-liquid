---
title: Where array filter
description: Creates an array including only the objects with a given property value, or any truthy value by default. In this example, assume you have a list of products and you want to show your kitchen products separately. Using where, you can create an array containing only the products that have a "type" of "kitchen".
liquidjs: https://liquidjs.com/filters/where.html
shopify: https://shopify.github.io/liquid/filters/where/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/where
---
All products:
{% for product in products %}
- {{ product.title }}
{% endfor %}

{% assign kitchen_products = products | where: "type", "kitchen" %}

Kitchen products:
{% for product in kitchen_products %}
- {{ product.title }}
{% endfor %}

Say instead you have a list of products and you only want to show those that are available to buy. You can where with a property name but no target value to include all products with a truthy "available" value:

All products:
{% for product in products %}
- {{ product.title }}
{% endfor %}

{% assign available_products = products | where: "available" %}

Available products:
{% for product in available_products %}
- {{ product.title }}
{% endfor %}

The where filter can also be used to find a single object in an array when combined with the first filter. For example, say you want to show off the shirt in your new fall collection:

{% assign new_electronic = products | where: "type", "electronics" | first %}

Featured product: {{ new_electronic.title }}