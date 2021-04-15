---
layout: page
title: Committees
permalink: /about/committees
published: true
---

{% for committee in site.data.committees %}
## {{committee.name}}
#### {{committee.chairperson}}
{{committee.plans-goals}}
{% endfor %}
