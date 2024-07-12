---
layout: default
title: AI4SE People
---

# People

{% for category in site.data.people %}
## {{ category.category }}

{% for person in category.people %}
{% include person.html person=person %}
{% endfor %}
{% endfor %}
 
 