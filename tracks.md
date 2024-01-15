---
layout: default
title: Research Tracks
---

# Research Tracks

The current tracks are:

| Track  | PhD Candidate |
|--------|---------------|
{% for track in site.tracks -%}
{%- unless track.inactive -%}
 | [{{track.title}}]({{track.url | relative_url}}) | {{track.phd}} |
{%- endunless -%}
{% endfor -%}

<br/>