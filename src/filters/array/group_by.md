---
title: group_by
description: Group an array’s items by a given property.
liquidjs: https://liquidjs.com/filters/group_by.html
shopify: https://shopify.github.io/liquid/filters/group_by/
shopifyDev: https://shopify.dev/docs/api/liquid/filters/group_by
---
### Input
<pre>
{% raw %}
{{ members | group_by: "graduation_year" | json: 2 }}
{% endraw %}
</pre>

### Output
<pre>
{{ members | group_by: "graduation_year" | json: 2 }}
</pre>