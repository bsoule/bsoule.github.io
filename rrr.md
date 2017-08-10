---
layout: page
title: Races Results & Records 
permalink: /rrr/
---
Here are some events that I've participated in, and personal records I'm proud of.
{% for rrr in site.data.records %}
  * {{ rrr }}
{% endfor %}
