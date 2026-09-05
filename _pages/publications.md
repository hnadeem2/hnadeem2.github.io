---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: false
---

{% include base_path %}

Selected publications and preprints (7 total; 5 first or co-first author). †Equal contribution.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
