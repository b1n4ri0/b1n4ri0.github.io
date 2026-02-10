---
layout: default
title: Home
---

## Recent Advisories
{% for advisory in site.advisories limit:10 %}
* **[{{ advisory.cve_id }}]** - [{{ advisory.title }}]({{ advisory.url }}) ({{ advisory.severity }})
{% endfor %}