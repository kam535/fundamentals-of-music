---
layout: page
permalink: /tabletest/
title: tabletest
description: a table test
nav: false
nav_order: 
---

{% assign row = site.data.metadata_fundamentals[0] %}
{{ row | inspect }}

{% assign row = site.data.metadata_fundamentals[0] %}
{% for pair in row %}
  {{ pair | inspect }}
{% endfor %}

<table>
  {% for row in site.data.metadata_fundamentals %}
    {% if forloop.first %}
    <tr>
      {% for pair in row %}
        <th>{{ pair[0] }}</th>
      {% endfor %}
    </tr>
    {% endif %}
  {% endfor %}
</table>