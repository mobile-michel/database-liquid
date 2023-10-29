---
title: Slice array filter
description: Returns a substring of 1 character beginning at the index specified by the first argument. An optional second argument specifies the length of the substring to be returned. String indices are numbered starting from 0.
liquidjs: https://liquidjs.com/filters/slice.html
shopify: https://shopify.github.io/liquid/filters/slice/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/slice
---
{{ "Liquid" | slice: 0 }}  
{{ "Liquid" | slice: 2 }}  
{{ "Liquid" | slice: 2, 5 }}  
If the first argument is a negative number, the indices are counted from the end of the string:  
{{ "Liquid" | slice: -3, 2 }}