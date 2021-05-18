---
layout: archive
title: "Work Experience"
permalink: /experience/
author_profile: true
---

{% for post in site.experience reversed %}
  {% include archive-single.html %}
{% endfor %}
