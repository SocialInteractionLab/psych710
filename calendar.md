---
layout: page
title: Calendar
description: The weekly event calendar.
---

{% for event in site.events %}
{{ event }}
{% endfor %}
