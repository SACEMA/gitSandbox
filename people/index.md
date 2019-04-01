---
layout: page
title: 2019-01-04
summary: People attending the intro to git session.
---

{% for profile in site.people %}

<div style="font-size:18px">
<h3> {{ profile.name }} {{ profile.surname }}</h3>
<p style="font-size:14px"> <strong>{{ profile.theme }}</strong></p><p style="font-size:14px"> <em>{{ profile.topic }}</em></p>
</div>
{% endfor %}
