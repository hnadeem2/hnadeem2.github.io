---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- {% if author.googlescholar %} -->

<!-- {% endif %} -->

{% include base_path %}

You can also find my articles on <a href="https://scholar.google.com/citations?user=vFtQG3YAAAAJ&hl=en&oi=sra">my Google Scholar profile</a>.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
