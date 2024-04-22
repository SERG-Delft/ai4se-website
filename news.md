---
layout: default
title: AI4SE News
---

# AI4SE News

{% for item in site.news -%}

{{item.date | date_to_long_string}}: [{{item.title}}]({{item.url | relative_url}})

{% endfor %}

<br/>