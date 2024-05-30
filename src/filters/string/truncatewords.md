---
title: truncatewords
description: shortens a string down to the number of words passed as an argument. If the specified number of words is less than the number of words in the string, an ellipsis (…) is appended to the string.
version: 1.9.1
works: true
---
{% assign formula = "Ground control to Major Tom." | truncatewords: 3 %}
{% render 'example', number: "1", text: '"Ground control to Major Tom." | truncatewords: 3', code: formula %}