---
title: rstrip
description: removes all whitespace (tabs, spaces, and newlines) from the right side of a string. It does not affect spaces between words.
version: 1.9.1
works: true
---
{% assign formula = "          So much room for activities!          " | rstrip %}
{% render 'example', number: 1, text: '"          So much room for activities!          " | rstrip', code: formula %}