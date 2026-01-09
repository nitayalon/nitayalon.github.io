---
layout: archive
title: "Projects"
permalink: /active_research/
author_profile: true
---

Here you can find a description of my currecnt, future and past projects.  

## Cognitive Hierarchies in MARL
I am very interested in how cognitive hierarchies influence agent behavior and decision-making processes in MARL environments. This involves studying how agents model and predict the actions of other agents and the impact of these models on overall system performance.

### Adapted Thoery of Mind
My long term research goal is to model how agents should *adapt* their ToM (depth nad width) when interacting with other agents in an open world, open agent domain.

### Deception in Multi-Agent Systems
In this contexnt, a key area of my research is the emergence of deceptive strategies in multi-agent systems. I investigate how and why agents develop deceptive behaviours and the implications of these behaviours for the stability and efficiency of multi-agent interactions. In addition, my work also explains how anti-social behaviours arise from deceptive environement. Lastly, I propose a model-free solution to cope with deceptive opponents with bounded computational resources.

#### Relevant Papers:
<ul>
  {% for post in site.publications %}
    {% if post.project == "deception_in_marl" %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

## Human-AI interaction in Cooperative Multi-Agent text games (the CodeWords project)

In this project my aim is to model, measure and improve human-ai cooperation in the game of CodeWords (variation of CodeNames). 
Particularly, my interest lies in *adapting* to new counterparts (zero-shot interaction), in a limited communication game.
