---
layout: default
title: Home
---

# Neutrino Security Research

Welcome to my personal research space. I focus on hardware hacking, vulnerability research, and coordinated disclosure.

## Recent Advisories
{% for advisory in site.advisories limit:5 %}
* **[{{ advisory.cve_id }}]** - [{{ advisory.title }}]({{ advisory.url }}) ({{ advisory.severity }})
{% endfor %}

## Active Projects
{% for project in site.projects limit:3 %}
* [{{ project.title }}]({{ project.url }})
{% endfor %}

---
[GitHub](https://github.com/b1n4ri0)
