---
title: Rayén
layout: default
---

I am a Chilean artist working with communities, bodies and intimacy.

My previous projects include:

{% for project in site.projects %}
    {% if project.featured %}
* __[{{ project.title }}]({{ project.url }})__ - _{{ project.tagline }}_
    {% endif %}
{% endfor %}

I am currently doing a residency at [ARE](https://www.areholland.com/) in Enschede, Netherlands. If you are nearby, come and say hello!

You can email me at rayen@rayen.studio.

---

_The code for this website is open source and available [here](https://github.com/joekroese/rayen.studio)._
