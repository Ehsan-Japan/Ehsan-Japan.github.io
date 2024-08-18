---
layout: archive
title: "Research"
permalink: /Research/
author_profile: true
---
## Time-Efficient Tuning of Quantum Dots into Single Dot State

Gate electrodes are designed to adjust the electrical potential, but these adjustments also create a large parameter space, making it time-consuming to explore it manually and impractical to scale for circuits with millions of qubits.
Recenlty,The use of machine-learning techniques for parameter estimation and tuning of quantum systems has shown great promise.
![tuning](/images/tuning.png)
Autotuning" is defined as the process of identifying a range of gate voltages where the device is in a specific electrical configuration.

For my master's thesis, I developed a closed-loop feedback system to tune the fine gates of a quadruple quantum dot device into a single dot state. 
<!-- A Long Short-Term Memory (LSTM) neural network was used to train a machine learning model capable of distinguishing between currents with Coulomb peak traces and those without. 
This method was inspired by the Ray-based Classification framework. -->
By effectively tuning quantum dot devices into single-dot regimes, I aimed to address scalability challenges in spin qubit systems by minimizing the need for manual tuning.

![Forming single dot by ray method](/images/ray_method.png)

<!-- is based on [Ray-based classification framework](https://journals.aps.org/prxquantum/abstract/10.1103/PRXQuantum.2.020335) and -->