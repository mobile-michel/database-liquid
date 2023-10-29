---
title: The LiquidJS template language
description: Liquid uses a combination of output (with optional filters) and tags inside template files to display dynamic content.
layout: base
---
## LiquidJS
- [Object](objects): contain the content... `{% raw %}{{ page }}{% endraw %}`
- [Tag](tags): create the logic and control flow... `{% raw %}{% if user %}{% endraw %}`
- [Filter](filters): change the output of object or variable... `{% raw %}{{ object | filter }}{% endraw %}`

## Interesting links
- [LiquidJS](https://liquidjs.com/), the JavaScript version.
- [The Shopify Cheat Sheet](https://www.shopify.com/partners/shopify-cheat-sheet)
- [Shopify API reference docs](https://shopify.dev/docs/api), with all the proprietary objects.
- [Liquid on Shopify](https://shopify.github.io/liquid/), the open-source template language.