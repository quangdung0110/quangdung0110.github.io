---
layout: archive
title: "Publications"
permalink: /_publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my publications on <u><a href="https://scholar.google.com/citations?user=_YYwzhQAAAAJ&hl=en">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
