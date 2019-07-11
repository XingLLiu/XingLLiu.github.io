---
title: "My academic CV"
collection: cv
premalink: /cv/cv_academic
excerpt: "This is my academic CV."
paperurl: "http://academicpages.github.io/files/cv.pdf"
---
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}