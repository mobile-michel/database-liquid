---
title: Tags
description: Tags create the logic and control flow for templates. The curly brace percentage delimiters {% and %} and the text that they surround do not produce any visible output when the template is rendered. This lets you assign variables and create conditions or loops without showing any of the Liquid logic on the page.
tags: primary
pagination:
    data: collections.tags
    size: 10
    alias: items
---
{%- for post in items %}
- [{{ post.data.title }}]({{ post.url }}): {{ post.data.description }}
{%- endfor %}