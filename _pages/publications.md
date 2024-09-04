---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>

## Journal papers

{% include base_path %}

{% for post in site.journal_publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Workshop papers
{% include base_path %}

{% for post in site.workshop_publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Ongoing work

Here you can find my current drafts:
* [$\aleph$-IPOMDP](https://nitayalon.github.io/files/aleph_IPOMDP_arXiv.pdf)
