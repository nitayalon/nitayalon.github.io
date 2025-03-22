---
layout: archive
title: "Projects"
permalink: /active_research/
author_profile: true
---

# Projects
Here you can find a description of my currecnt, future and past projects.  

## Cognitive Hierarchies in MARL
I am particularly interested in how cognitive hierarchies influence agent behavior and decision-making processes in MARL environments. This involves studying how agents model and predict the actions of other agents and the impact of these models on overall system performance.

### Deception in Multi-Agent Systems
In this contexnt, a key area of my research is the emergence of deceptive strategies in multi-agent systems. I investigate how and why agents develop deceptive behaviors and the implications of these behaviors for the stability and efficiency of multi-agent interactions.

#### Relevant Papers:
<ul>
  {% for post in site.publications %}
    {% if post.project == "deception_in_marl" %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

### Cooperation in Multi-Agent text games (the CodeNames project)
