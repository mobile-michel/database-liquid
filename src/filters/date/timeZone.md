---
title: Date timezone filter
description: By default, dates will be converted to local timezone before output.
liquidjs: https://liquidjs.com/filters/date.html#TimeZone
shopify: https://shopify.github.io/liquid/filters/date/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/date
---
You can override that by,
- setting a timezone for each individual date filter via the second parameter
- using the timezoneOffset LiquidJS option
  - Its default value is your local timezone offset which can be obtained by new Date().getTimezoneOffset()
  - Offset can be set as,
    - minutes: -360 means '+06:00' and 360 means '-06:00'
    - timeZone ID: Asia/Colombo or America/New_York
  - Use minutes for better performance with repeated processing of templates with many dates like, converting template for each email recipient
- Refer here for TZ database values

## Examples
// equivalent to setting `options.timezoneOffset` to `360`  
{{ "1990-12-31T23:00:00Z" | date: "%Y-%m-%dT%H:%M:%S", 360 }}  
{{ "1990-12-31T23:00:00Z" | date: "%Y-%m-%dT%H:%M:%S", "Asia/Colombo" }}