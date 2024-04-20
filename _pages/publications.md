---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

  <div class="wordwrap">Here is the list of my articles</a>.</div>
  
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
