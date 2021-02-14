---
layout: page
title: Senators
permalink: /senators/
---

{% for senator in site.data.senators %}
### {{senator.name}} - {{senator.major}} {{senator.year}}

Email: [{{senator.email}}](mailto:{{senator.email}})

![{{senator.name}}]({{senator.image}})

{{senator.bio}}

{% endfor %}
