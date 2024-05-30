---
title: slice
description: Returns a substring of 1 character beginning at the index specified by the first argument. An optional second argument specifies the length of the substring to be returned. String indices are numbered starting from 0.
version: 1.9.1
works: true
---
{% assign formula = "Liquid" | slice: 0 %}
{% render 'example', number: "1", text: '"Liquid" | slice: 0', code: formula %}
{% assign formula = "Liquid" | slice: 2 %}
{% render 'example', number: "2", text: '"Liquid" | slice: 2', code: formula %}
{% assign formula = "Liquid" | slice: 2, 5 %}
{% render 'example', number: "3", text: '"Liquid" | slice: 2, 5', code: formula %}
{% assign formula = "Liquid" | slice: -3, 2 %}
{% render 'example', number: "4", text: '"Liquid" | slice: -3, 2', code: formula %}