---
layout: default
---

{% for item in site.data.navigation %}
  <a href="{{ item.url }}">{{ item.text }}</a>
{% endfor %}

# Welcome to your website
