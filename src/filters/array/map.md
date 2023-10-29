---
title: Map array filter
description: Creates an array of values by extracting the values of a named property from another object.
liquidjs: https://liquidjs.com/filters/map.html
shopify: https://shopify.github.io/liquid/filters/map/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/map
---
In this example, assume the object site.pages contains all the metadata for a website. Using assign with the map filter creates a variable that contains only the values of the category properties of everything in the site.pages object:
{% assign all_categories = site.pages | map: "category" %}

{% for item in all_categories %}
- {{ item }}
{% endfor %}

Creates an array of values from a specific property of the items in an array:

{% assign product_titles = collection.products | map: 'title' %}
{{ product_titles | join: ', ' }}