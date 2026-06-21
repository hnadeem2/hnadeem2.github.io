---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: false
---

{% include base_path %}

Selected publications and preprints.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
