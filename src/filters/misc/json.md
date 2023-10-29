---
title: Json misc filter
description: Convert values to string via JSON.stringify(), for debug purpose.
liquidjs: https://liquidjs.com/filters/json.html
shopify: absent !
shopifyDev: https://shopify.dev/docs/api/liquid/filters/json
---
{% assign arr = "foo bar coo" | split: " " %}
{{ arr | json }}