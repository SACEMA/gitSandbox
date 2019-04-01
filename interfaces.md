---
layout: page
title: Git Interfaces
summary: Ways to use git.
---

{% for gui in site.interfaces %}
<div style="font-size:18px">
<h3> {{ gui.interface }}</h3>
<p> {{ gui.summary }} </p>
</div>
{% endfor %}
