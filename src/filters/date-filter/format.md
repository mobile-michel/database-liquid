---
title: Date format filter
description: Converts a timestamp into another date format.
liquidjs: https://liquidjs.com/filters/date.html
shopify: https://shopify.github.io/liquid/filters/date/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/date
---
---
LiquidJS tries to be conformant with Shopify/Liquid which is using Ruby’s core Time#strftime(string)
- Refer format flags
- Not all options are supported though - refer differences here
The input is firstly converted to Date object via new Date()
Date format can be provided individually as a filter option
- If not provided, then %A, %B %-e, %Y at %-l:%M %P %z format will be used as default format
- Override this using dateFormat LiquidJS option, to set your preferred default format for all date filters

## Examples
The file site.json was published on {{ site.published_at | date: '%a, %b %d, %y' }}

Today, the date & time is {{ "now" | date: "%d-%m-%Y %H:%M" }}

Special date: {{ '1990-12-31T23:30:28Z' | date: '%d%q of %b %Y at %I:%M %P', -330 }}