---
layout: page
title: "Next"
description: "Next seminars"
header-img: "img/ens2.png"
---

Next seminars:


{% for oneitem in site.data.next %}
<p>
  {{ oneitem.date }}, {{ oneitem.time }}, room {{ oneitem.room }}.<br/>
  <a href="{{ oneitem.url }}">{{ oneitem.speaker }}</a>  ({{ oneitem.affiliation }})<br/>
  <b>Title:</b> <i>{{ oneitem.title }}</i><br/>
  <b>Abstract:</b> {{ oneitem.abstract }}
  </p>
{% endfor %}


For 2016-2017, the planed dates are:

- tuesday 11/10
- tuesday 8/11
- tuesday 13/12
