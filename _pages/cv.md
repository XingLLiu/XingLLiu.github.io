---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
---

{% include base_path %}

{% for post in site.cv reversed %}
  {% include archive-single.html %}
{% endfor %}
