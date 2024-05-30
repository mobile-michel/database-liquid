---
title: remove_first
description: removes only the first occurrence of the specified substring from a string.
version: 1.9.1
works: true
---
{% assign formula = "I strained to see the train through the rain" | remove_first: "rain" %}
{% render 'example', number: 1, text: '"I strained to see the train through the rain" | remove_first: "rain"', code: formula %}