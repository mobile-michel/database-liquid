---
title: lstrip
description: removes all whitespace (tabs, spaces, and newlines) from the left side of a string. It does not affect spaces between words.
version: 1.9.1
works: true
---
{% assign formula = "          So much room for activities!          " | lstrip %}
{% render 'example', number: 1, text: '"          So much room for activities!          " | lstrip', code: formula %}