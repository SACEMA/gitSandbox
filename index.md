---
layout: page
title: Git Sandbox
summary: People attending the intro to git session on 2019-01-04.
---

{% for profile in site.people %}
<div style="font-size:18px">
<h3> {{ profile.name }} {{ profile.surname }} {%if profile.github contains ""%}
        <a href="https://github.com/{{ profile.github }}"><i class="fab fa-github"></i></a>
        {%endif%}</h3>
<p style="font-size:14px"> <strong>{{ profile.theme }}</strong></p><p style="font-size:14px"> <em>{{ profile.topic }}</em></p>
</div>
{% endfor %}
