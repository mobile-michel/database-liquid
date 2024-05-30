---
title: capitalize
description: makes the first character of a string capitalized.
version: 1.9.1
works: true
---
{% assign formula = "title" | capitalize %}
{% render 'example', number: 1, text: '"title" | capitalize', code: formula %}
{% assign formula = "my great title" | capitalize %}
{% render 'example', number: 2, text: '"my great title" | capitalize', code: formula %}