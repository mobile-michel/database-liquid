---
title: replace_last
description: replaces only the last occurrence of the first argument in a string with the second argument.
version: 10.2.0
works: true
---
{% assign formula = "Take my protein pills and put my helmet on" | replace_last: "my", "your" %}
{% render 'example', number: 1, text: '"Take my protein pills and put my helmet on" | replace_last: "my", "your"', code: formula %}