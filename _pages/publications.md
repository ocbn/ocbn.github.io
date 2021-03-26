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
{% for post in site.publications reversed %}
  {% if post.type == 1 %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## National Conference Proceedings
{% for post in site.publications reversed %}
  {% if post.type == 2 %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
## International Conference Proceedings
{% for post in site.publications reversed %}
  {% if post.type == 3 %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
