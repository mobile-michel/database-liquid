---
title: date-to-xmlschema
description: To get the current time, pass the special word "now" or "today" as input.
liquidjs: https://liquidjs.com/filters/{{title}}.html
shopify: https://shopify.github.io/liquid/filters/date/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/date
---
Note that the value will be the current time of when the page was last generated from the template, not when the page is presented to a user if caching or static site generation is involved.

## Examples
Last updated on: {{ "now" | date: "%Y-%m-%d %H:%M" }}  
Last updated on: {{ "today" | date: "%Y-%m-%d %H:%M" }}