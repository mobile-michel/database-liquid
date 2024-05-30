---
title: prepend
description: adds the specified string to the beginning of another string.
version: 1.9.1
works: true
---
{% assign formula = "apples, oranges, and bananas" | prepend: "Some fruit: " %}
{% render 'example', number: 1, text: '"apples, oranges, and bananas" | prepend: "Some fruit: "', code: formula %}
{% assign formula = "/index.html" | prepend: "example.com" %}
{% render 'example', number: 2, text: '"/index.html" | prepend: "example.com"', code: formula %}