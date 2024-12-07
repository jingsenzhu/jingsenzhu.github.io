---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

**Note: \* denoted equal contribution**

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

