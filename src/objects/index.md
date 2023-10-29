---
title: Objects
description: Tags create the logic and control flow for templates. The curly brace percentage delimiters {% and %} and the text that they surround do not produce any visible output when the template is rendered. This lets you assign variables and create conditions or loops without showing any of the Liquid logic on the page.
tags: primary
layout: base
---
### It's called "Output" in LiquidJS
- an output consists of a value and a list of filters, which is optional, wrapped between {% raw %}{{ }}{% endraw %}

### Six types
- string... "characters"
- number
- boolean... true or false
- nil... special empty value when no results
- array... list of variables of any type (accessing a specific item = [1])
- emptyDrop