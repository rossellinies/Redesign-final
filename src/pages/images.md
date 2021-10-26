---
layout: layouts/images.html
pageTitle: Images
navTitle: Images
date: 2019-02-01
---

{% for filename in images %}
<img src="/img/{{ filename }}" alt="A nice picture of apples." srcset="">
{% endfor %}

[Home](/)
