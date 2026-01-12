---
layout: archive
title: "Projects"
permalink: /active_research/
author_profile: true
---

Here you can find a description of my current, future and past projects.  

## Cognitive Hierarchies in MARL
I am very interested in how cognitive hierarchies influence agent behavior and decision-making processes in MARL environments. This involves studying how agents model and predict the actions of other agents and the impact of these models on overall system performance.

### Adaptive Theory of Mind
My long-term research goal is to model how agents should *adapt* their ToM (depth and width) when interacting with other agents in an open world, open agent domain. Consider how humans use their mentalization - we form beliefs about others' feelings and try to predict how our actions will affect them - but in some cases (like when buying a coffee), it makes no sense to "predict" the Barista's next move - it's both predictable and meaningless. We have a neural regulation mechanism that *activates* ToM where needed and only *when* needed - avoiding over or under usage.

### Deception in Multi-Agent Systems
In this context, a key area of my research is the emergence of deceptive strategies in multi-agent systems. I investigate how and why agents develop deceptive behaviors and the implications of these behaviors for the stability and efficiency of multi-agent interactions. In addition, my work also explains how anti-social behaviors arise from deceptive environments. Lastly, I propose a model-free solution to cope with deceptive opponents with bounded computational resources.

#### Relevant Papers:
<ul>
  {% for post in site.publications %}
    {% if post.project == "deception_in_marl" %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

### Human-AI Interaction in Word Association Games

In this project, my aim is to model, measure and improve human-AI cooperation in the game of CodeWords (a variation of CodeNames). 
Particularly, my interest lies in *adapting* to new counterparts (zero-shot interaction) in a limited communication game.
