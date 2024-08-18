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
I do research on automated tuning of gate-defined quantum dots.<br>
I am advised by Professor Takafumi Fujita and Professor Akira Oiwa.
![tuning](/images/tuning.png)
## Research Interests

My main research interest lies in the intersection of Machine Learning and Quantum Computing.
Currently I am doing research on developping methods for automatically tuning spin qubits in Semiconductor Quantum dots. 
I use machine learning and quantum dot simulation while performing experiments to answer the following questions:
  * How can we accelerate and automate the tuning procedure of semiconductor spin qubits?
  * How can we automatically extract virtual gates to mitigate cross-coupling effects in Quantum dots? 


## Research Projects
### 1. Automated and Fast Voltage Tuning Methods for Spin Qubits
To perform quantum computation using spins of electrons in gated-defined quantum dots, electrons must be confined within a precisely controlled potential state.Typically, electrons in quantum dots experience a random, non-uniform potential (left), which needs to be transformed into a controlled, desired potential (right), an essential step in performing quantum gate operations.<br>


My research focuses on creating a fast, autotuning method to adjust potential in quantum dots to form a single quantum dot.[Read more](Research.md)
<!-- This method is currently being extended for tuning to a double dot configuration.  -->

### 2. Virtual Gate Extraction Techniques for Cross-Coupling Mitigation
Although spin qubits in quantum dots are a key platform for fault-tolerant quantum computing, the close proximity of surface gate electrodes causes cross-coupling effects, which challenge scalability. 
![tuning](/images/virtual_gate.png){: width="300px"}

I’m currently developing an end-to-end method to extract virtual gates in simulated double quantum dot stability diagrams.This method used image recognition to detect transition lines in the stability diagrams and applies a transformation matrix to the voltage space recursively, adjusting the angle distribution until horizontal and vertical angles are achieved.[Read more](Research.md)
