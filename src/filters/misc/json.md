---
title: json
description: Convert values to string via JSON.stringify(), for debug purpose.
version: 9.10.0
works: true
---
### Example 2
input: 
<pre><code>{% raw %}{% assign arr = "foo bar coo" | split: " " %}
{{ arr | json }}{% endraw %}
</code></pre>

output:
<pre><code>{% assign arr = "foo bar coo" | split: " " %}{{ arr | json }}</code></pre>

### Space

Added in v10.11.0

An additional space parameter can be specified to format the JSON:

input:

<pre><code>{% raw %}{% assign arr = "foo bar coo" | split: " " %}
{{ arr | json: 4 }}{% endraw %}
</pre></code>

output:

<pre><code>{% assign arr = "foo bar coo" | split: " " %}{{ arr | json: 4 }}</code></pre>