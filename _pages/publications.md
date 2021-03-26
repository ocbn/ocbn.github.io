---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## Thesis
{% for post in site.publications.thesis reversed %}
  {% include archive-single.html %}
{% endfor %}

## National Conference Proceedings
{% for post in site.publications.ncp reversed %}
  {% include archive-single.html %}
{% endfor %}
