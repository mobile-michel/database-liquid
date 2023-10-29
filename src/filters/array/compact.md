---
title: Compact array filter
description: Removes any nil values from an array. For this example, assume site.pages is an array of content pages for a website, and some of these pages have an attribute called category that specifies their content category. If we map those categories to an array, some of the array items might be nil if any pages do not have a category attribute.
liquidjs: https://liquidjs.com/filters/compact.html
shopify: https://shopify.github.io/liquid/filters/compact/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/compact
---
{% assign site_categories = site.pages | map: "category" | compact %}

{% for category in site_categories %}
- {{ category }}
{% endfor %}