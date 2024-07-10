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
* To leverage machine learning for metal additive manufacturing (AM) while reducing the need for large datasets, we introduce a physics-informed neural network (PINN) framework. This method combines data with fundamental physical principles, such as conservation laws of momentum, mass, and energy. Additionally, we propose a method for enforcing Dirichlet boundary conditions using a Heaviside function, which improves accuracy and accelerates learning. The PINN framework is applied to two metal manufacturing problems, including the 2018 NIST AM-Benchmark test series.

## Interface coupled formulation in overset method
<br/><img src='/images/Overset_formulation.png'>
* We addressed the issues of poor numerical stability, low parallel efficiency, and limited adaptability to complex engineering problems in the old overlapping grid method by proposing a multi-medium interface coupling approach. This method includes a synchronous update strategy for multiple subdomains and a composite Matrix-free computational technique. It has been successfully applied to simulations of offshore wind turbines, tidal turbines, and gear quenching, showing excellent agreement with experimental results.
