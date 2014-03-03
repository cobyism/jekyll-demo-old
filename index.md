---
layout: default
---

Here are some things I have written:

{% for post in site.posts %}
  - [{{post.title}}]({{ post.url }}) — {{ post.date | date_to_string }}
{% endfor %}

I might write more Soon™.
