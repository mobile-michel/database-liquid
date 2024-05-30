---
title: remove
description: removes every occurrence of the specified substring from a string.
version: 1.9.1
works: true
---
{% assign formula = "I strained to see the train through the rain" | remove: "rain" %}
{% render 'example', number: 1, text: '"I strained to see the train through the rain" | remove: "rain"', code: formula %}