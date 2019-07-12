---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
---

{% include base_path %}

# {% for post in site.cv reversed %}
#   {% include archive-single.html %}
# {% endfor %}

{% for post in site.cv %}
  {% include archive-single.html %}
{% endfor %}

{% include http://XingLLiu.github.io/files/cv_academic.pdf %}
