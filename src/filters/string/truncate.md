---
title: truncate
description: shortens a string down to the number of characters passed as an argument. If the specified number of characters is less than the length of the string, an ellipsis (…) is appended to the string and is included in the character count.
version: 1.9.1
works: true
---
{% assign formula = "Ground control to Major Tom." | truncate: 20 %}
{% render 'example', number: "Basic usage", text: '"Ground control to Major Tom." | truncate: 20', code: formula %}
{% assign formula = "Ground control to Major Tom." | truncate: 25, ", and so on" %}
{% render 'example', number: "Custom ellipsis", text: '"Ground control to Major Tom." | truncate: 25, ", and so on"', code: formula %}
{% assign formula = "Ground control to Major Tom." | truncate: 20, "" %}
{% render 'example', number: "No ellipsis", text: '"Ground control to Major Tom." | truncate: 20, ""', code: formula %}