---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>

{% include base_path %}
## Journal Papers
{% for post in site.publications reversed %}
  {% if post.type == "journal" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Workshop Papers
{% for post in site.publications reversed %}
  {% if post.type == "workshop" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<!-- {% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->

## Ongoing work

Here you can find my current drafts:
* [$\aleph$-IPOMDP](https://nitayalon.github.io/files/aleph_IPOMDP_arXiv.pdf)
