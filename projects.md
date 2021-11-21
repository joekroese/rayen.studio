---
title: All Projects
layout: default
---

{% for project in site.projects %}
* __[{{ project.title }}]({{ project.url }})__ - _{{ project.tagline }}_
{% endfor %}
