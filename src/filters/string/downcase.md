---
title: downcase
description: makes each character in a string lowercase. It has no effect on strings which are already all lowercase.
version: 1.9.1
works: true
---
{% assign formula = "Parker Moore" | downcase %}
{% render 'example', number: 1, text: '"Parker Moore" | downcase', code: formula %}
{% assign formula = "apple" | downcase %}
{% render 'example', number: 2, text: '"apple" | downcase', code: formula %}