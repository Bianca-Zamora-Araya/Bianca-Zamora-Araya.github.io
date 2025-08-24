---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}
## Teaching Assistantships
---
{% for post in site.teaching reversed %}
  {% include archive-single.html %}{% endfor %}

{% include base_path %}
## Teaching Innovation Grants
---
{% for post in site.teachinginnovations reversed %}
  {% include archive-single.html %}{% endfor %}
