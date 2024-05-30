---
title: replace_first
description: replaces only the first occurrence of the first argument in a string with the second argument.
version: 1.9.1
works: true
---
{% assign formula = "Take my protein pills and put my helmet on" | replace_first: "my", "your" %}
{% render 'example', number: 1, text: '"Take my protein pills and put my helmet on" | replace_first: "my", "your"', code: formula %}