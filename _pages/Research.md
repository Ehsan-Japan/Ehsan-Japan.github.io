---
layout: archive
title: "Research"
permalink: /Research/
author_profile: true
---

# Projects

## Time-Efficient Tuning of Quantum Dots into Single Dot State

For my master's thesis, I developed a closed-loop feedback system to tune the fine gates of a quadruple quantum dot device into a single dot state. 
<!-- A Long Short-Term Memory (LSTM) neural network was used to train a machine learning model capable of distinguishing between currents with Coulomb peak traces and those without. 
This method was inspired by the Ray-based Classification framework. -->
By effectively tuning quantum dot devices into single-dot regimes, I aimed to address scalability challenges in spin qubit systems by minimizing the need for manual tuning.

![Forming single dot by ray method](/images/ray_method.png)

## Research Objectives

### Automated and High-Speed Voltage Tuning Techniques for Spin Qubits
![tuning](/images/tuning2.png)

### Development of Spin Qubit Stabilization Using Feedback Control
![tuning](/images/tuning.png)

{% if site.talkmap_link == true %}
<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>
{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}