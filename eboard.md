---
layout: page
title: eBoard
permalink: /eboard/
---

{% for eboard in site.data.eboard %}
### {{eboard.name}} - {{eboard.major}} {{eboard.position}} 

Email: [{{eboard.email}}](mailto:{{eboard.email}})

![{{eboard.name}}]({{eboard.image}})

{{eboard.bio}}

{% endfor %}