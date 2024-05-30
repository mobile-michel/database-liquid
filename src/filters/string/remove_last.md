---
title: remove_last
description: removes only the last occurrence of the specified substring from a string.
version: 10.2.0
works: true
---
{% assign formula = "I strained to see the train through the rain" | remove_last: "rain" %}
{% render 'example', number: 1, text: '"I strained to see the train through the rain" | remove_last: "rain"', code: formula %}