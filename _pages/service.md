---
layout: archive
title: "Service"
permalink: /service/
author_profile: true
---

{% include base_path %}

* Ph.D in Version Control Theory, GitHub University, 2018 (expected)
* M.S. in Jekyll, GitHub University, 2014
* B.S. in GitHub, GitHub University, 2012

{% for post in site.service reversed %}
  {% include archive-single.html %}
{% endfor %}
