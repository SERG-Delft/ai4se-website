---
layout: default
title: AI4SE Publications
---

# Publications

{% for publication in site.data.publications %}

1. **{{publication.title}}.**
  {%- if publication.author %}
  {{publication.author}}.
  {%- elsif  publication.authors -%}
    {%- for author in publication.authors %}
      {{author}}{% if forloop.last %}.{% else %},{% endif %}
    {%- endfor -%}
  {%- endif -%}
  {% if publication.venue %}
    {{publication.venue}},
  {%- endif %}
    {{publication.year}}.
  {%- if publication.journal %}
    {{publication.journal}}.
  {%- endif -%}
  {%- if publication.award %}
    🏆 {{publication.award}}.
  {%- endif -%}
  {%- if publication.preprint %}
    [Preprint]({{publication.preprint}})
  {%- endif -%}
{% endfor %}