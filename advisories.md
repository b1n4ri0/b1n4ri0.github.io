---
layout: default
title: Advisories
---

## Recent Advisories
{% for advisory in site.advisories %}
* **[{{ advisory.cve_id }}]** - [{{ advisory.title }}]({{ advisory.url }})
{% endfor %}
