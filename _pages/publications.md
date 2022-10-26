---
layout: archive
title: "Projects & Publications"
permalink: /publications/
author_profile: true
---

Brief list of recent projects. Please refer to my CV for a complete (and updated) list of projects and internship/FT outcomes.
(Last updated : 24/10/2022)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
