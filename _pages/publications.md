---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on my <u><a href="https://scholar.google.com/citations?user=8kc1CN0AAAAJ&hl=tr" stye="text-decoration:none!important;">Google Scholar profile</a>.</u>

{% include base_path %}

## Thesis
{% for post in site.publications reversed %}
  {% if post.type == 1 %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Conference Proceedings
{% for post in site.publications reversed %}
  {% if post.type == 2 %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
## Articles
{% for post in site.publications reversed %}
  {% if post.type == 3 %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
