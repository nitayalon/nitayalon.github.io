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

## Conference Papers:
{% for post in site.publications reversed %}
  {% if post.type == "conference" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}


## Workshop Papers
{% for post in site.publications reversed %}
  {% if post.type == "workshop" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}


## Preprints

Here you can find my current work:
{% for post in site.publications reversed %}
  {% if post.type == "preprint" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}