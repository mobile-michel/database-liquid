---
title: Append string filters
description: Concatenates two strings and returns the concatenated value.
liquidjs: https://liquidjs.com/filters/append.html
shopify: https://shopify.github.io/liquid/filters/append/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/append/
---
{{ "/my/fancy/url" | append: ".html" }}  
{% assign filename = "/index.html" %}
{{ "website.com" | append: filename }}