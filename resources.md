---
title: Resources
permalink: /resources
layout: default
---
 {%- for resource in site.resources -%}
      <li>
        <h3>
          <a class="post-link" href="{{ resource.url | relative_url }}">
            {{ resource.title | escape }}
          </a>
        </h3>
      </li>
 {%- endfor -%}