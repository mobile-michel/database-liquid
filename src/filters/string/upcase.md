---
title: upcase
description: makes each character in a string uppercase. It has no effect on strings which are already all uppercase.
version: 1.9.1
works: true
---
{% assign formula = "Parker Moore" | upcase %}
{% render 'example', number: 1, text: '"Parker Moore" | upcase', code: formula %}
{% assign formula = "APPLE" | upcase %}
{% render 'example', number: 2, text: '"APPLE" | upcase', code: formula %}