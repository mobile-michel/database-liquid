---
title: Capture variable tag
description: Captures the string inside of the opening and closing tags and assigns it to a variable. Variables created through capture are strings.
---
{% capture my_variable %}I am being captured.{% endcapture %}
{{ my_variable }}

Using capture, you can create complex strings using other variables created with assign:

{% assign favorite_food = "pizza" %}
{% assign age = 35 %}

{% capture about_me %}
I am {{ age }} and my favorite food is {{ favorite_food }}.
{% endcapture %}

{{ about_me }}