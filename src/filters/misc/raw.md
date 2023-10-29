---
title: Raw misc filter
description: Liquid filter that directly returns the value of the variable. Useful when outputEscape is set.
liquidjs: https://liquidjs.com/filters/raw.html
shopify: absent !
shopifyDev: absent !
---
## Auto escape
By default outputEscape is not set. That means LiquidJS output is not escaped by default, thus raw filter is not useful until outputEscape is set.

Input (outputEscape not set):

{{ "<" }}

{{ "<" | raw }}