---
title: Default misc filter
description: Allows you to specify a fallback in case a value doesn’t exist. default will show its value if the left side is falsy or empty (string or Array).
liquidjs: https://liquidjs.com/filters/default.html
shopify: https://shopify.github.io/liquid/filters/default/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/default
---
In this example, product_price is not defined, so the default value is used.  
  
{{ product_price | default: 2.99 }}  
  
In this example, product_price is defined, so the default value is not used.
{% assign product_price = 4.99 %}
{{ product_price | default: 2.99 }}  
  
In this example, product_price is empty, so the default value is used.
{% assign product_price = "" %}
{{ product_price | default: 2.99 }}