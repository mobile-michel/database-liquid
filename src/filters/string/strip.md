---
title: strip
description: removes all whitespace (tabs, spaces, and newlines) from both the left and right sides of a string. It does not affect spaces between words.
version: 1.9.1
works: true
---
{% assign formula = "          So much room for activities!          " | strip %}
{% render 'example', number: 1, text: '"          So much room for activities!          " | strip', code: formula %}