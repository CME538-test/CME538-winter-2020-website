---
layout: home
title: Home
nav_order: 0
description: 
---

# {{ site.description }}
{: .mb-2 }
{{ site.semester }}
{: .fs-6 .fw-300 }

{% if site.announcements %}
{{ site.announcements.last }}
{% endif %}

