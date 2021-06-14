---
layout: archive
title: "Resources"
permalink: /resources/
author_profile: false
---

{% for post in site.resources reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
