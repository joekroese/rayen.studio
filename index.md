---
layout: default
---

# Rayén

I am a Chilean artist working with communities and bodies.

My previous projects include:

{% for project in site.projects %}
    {% if project.featured %}
* __[{{ project.title }}]({{ project.url }})__ - _{{ project.tagline }}_
    {% endif %}
{% endfor %}

I am currently doing a residency at [ARE](https://www.areholland.com/) in Enschede, Netherlands. If you are nearby, come and say hello!

You can email me at rayen@rayen.studio.