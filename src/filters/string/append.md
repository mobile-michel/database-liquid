---
title: append
description: concatenates two strings and returns the concatenated value.
version: 1.9.1
works: true
---
{% assign formula = "/my/fancy/url" | append: ".html" %}
{% render 'example', number: 1, text: '"/my/fancy/url" | append: ".html"', code: formula %}
{% assign formula = "website.com" | append: "/index.html" %}
{% render 'example', number: 2, text: '"website.com" | append: "/index.html"', code: formula %}