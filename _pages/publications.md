---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Drafts

Here you can find my current drafts:
* [$\aleph$-IPOMDP](https://nitayalon.github.io/files/aleph_IPOMDP_arXiv.pdf)
