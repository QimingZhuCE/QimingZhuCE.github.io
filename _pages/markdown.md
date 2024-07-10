---
permalink: /markdown/
title: "Research work"
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---

## Mixed interface-capturing/interface-tracing formulation
<br/><img src='/images/Metal_AM_modeling_framework.png'>

* We developed a mixed interface-capturing/interface-tracing formulation for metal additive manufacturing modeling. The interface-capturing component is responsible for handling complex topological changes, such as the merging and separation of interfaces. The interface-tracking component constructs an explicit gas-metal interface, enabling the use of an explicit ray tracing-based laser model.

## Physics informed neural network based on Heaviside function
<br/><img src='/images/PINN_structure.png'>
* To fully exploit the power of machine learning for metal AM while alleviating the dependence on “big data”, we put forth a physics-informed neural network (PINN) framework that fuses both data and first physical principles, including conservation laws of momentum, mass, and energy, into the neural network to inform the learning processes. To the best knowledge of the authors, this is the first application of physics-informed deep learning to three dimensional AM processes modeling. Besides, we propose a hard-type approach for Dirichlet boundary conditions (BCs) based on a Heaviside function, which can not only exactly enforce the BCs but also accelerate the learning process. The PINN framework is applied to two representative metal manufacturing problems, including the 2018 NIST AM-Benchmark test series.
