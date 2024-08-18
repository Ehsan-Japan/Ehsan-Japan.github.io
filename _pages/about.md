---
permalink: /
title: "Hi there! I am Ehsan!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- ![Illustration of automated tuning](/images/automated.png){: .align-right width="200px"}  -->
<!-- ![autotuning agent](/images/automated.png){: .align-right width="300px"} -->
I am a second-year physics master student in the [Department of Quantum System Electronics](https://www.sanken.osaka-u.ac.jp/labs/qse/indexEN.html) at Osaka University, Japan.
I do research on automated tuning of gate-defined quantum dots.

I am advised by Professor Takafumi Fujita and Professor Akira Oiwa.

## Research Interests

My main research interest lies in the intersection of Machine learning and Quantum computing.
Currently I am doing research on developping methods for automatically tuning spin qubits in semiconductor quantum dots. 
I use machine learning and quantum dot simulation while performing experiments to answer the following questions:
  * How can machine learning improve qubit quality?
  * How can we accelerate and automate the tuning of semiconductor spin qubits?
  * How can we automatically extract virtual gates to mitigate cross-coupling effects in spin qubits for quantum computing

## Research Objectives
### 1. Automated and Fast Voltage Tuning Methods for Spin Qubits
To perform quantum computation, electrons must be carefully tuned to a desired potential state. Typically, the system begins with a random, non-uniform potential (left), which needs to be transformed into a controlled, uniform potential (right).
![tuning](/images/tuning2.png)

My research focuses on creating a fast, automated method to adjust potential landscapes to form a single quantum dot by using long short memory neural network. This method  is currently being extended for tuning to a double dot configuration. [Read more](Research.md)

### 2. Virtual Gate Extraction Techniques for Cross-Coupling Mitigation
Although spin qubits in quantum dots are a key platform for fault-tolerant quantum computing, the close proximity of surface gate electrodes causes cross-coupling effects, which challenge scalability. 
![tuning](/images/virtual_gate.png)

I’m currently developing an end-to-end method to extract virtual gates in simulated double quantum dot stability diagrams. This method uses image recognition to detect transition lines and applies a transformation matrix recursively, updating it based on angle distribution until horizontal and vertical angles are achieved.[Read more](Research.md)
