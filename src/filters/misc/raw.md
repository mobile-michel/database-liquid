---
title: raw
description: Liquid filter that directly returns the value of the variable. Useful when outputEscape is set.
version: 9.37.0
works: true
---
{% assign formula = "<" %}
{% render 'example', number: 1, text: '"<"', code: formula %}
{% assign formula = "<" | raw %}
{% render 'example', number: 2, text: '"<" | raw', code: formula %}
There is no differences in HTML code, so OutputEscape is not set!

## Auto escape
By default outputEscape is not set. That means LiquidJS output is not escaped by default, thus raw filter is not useful until outputEscape is set.