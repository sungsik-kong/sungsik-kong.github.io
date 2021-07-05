---
layout: archive
title: "Travel Notes"
permalink: /travel/
author_profile: true
---

{% include base_path %}

{% for post in site.travel reversed %}
  {% include archive-single.html %}
{% endfor %}
