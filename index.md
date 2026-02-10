---
layout: default
title: Home
---

# Neutrino Security Research

Welcome to my personal research space. I focus on hardware hacking, vulnerability research, and coordinated disclosure.

## Active Projects
{% for project in site.projects limit:3 %}
* [{{ project.title }}]({{ project.url }})
{% endfor %}
