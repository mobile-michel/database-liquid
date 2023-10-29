---
title: Date input filter
description: date works on strings if they contain well-formatted dates.
liquidjs: https://liquidjs.com/filters/date.html#Input
shopify: https://shopify.github.io/liquid/filters/date/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/date
---
Note that LiquidJS is using JavaScript Date to parse the input string, that means IETF-compliant RFC 2822 timestamps and strings in a version of ISO8601 are supported.

## Examples
{{ "1990-12-31T23:00:00Z" | date: "%Y-%m-%dT%H:%M:%S", 360 }}  
{{ "March 14, 2016" | date: "%b %d, %y" }}