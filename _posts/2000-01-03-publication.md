---
title: "PUBLICATION"
bg: white
color: dark
fa-icon: book
years: [2021, 2020, 2019, 2018, 2017]
---

## -prepints and recent publications-

{% bibliography -q @unpublished %}

{% for y in page.years %}
  <h3 class="year"><font size="+3">-{{y}}-</font></h3>
  {% bibliography -q !@unpublished[year={{y}}] %}
{% endfor %}
