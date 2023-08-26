---
title: "Physics-informed machine learning for surrogate modeling of wind pressure and optimization of pressure sensor placement"
collection: publications
permalink: /publication/paper1
excerpt: 'This paper is about PINN'
date: 2023-03-01
venue: 'Computational Mechanics'
paperurl: 'http://qimingzhuce.github.io/files/paper1.pdf'
---
This paper presents a predictive computational framework for surrogate modeling of pressure field and optimization of
pressure sensor placement for wind engineering applications. Firstly, a machine learning-derived surrogate model, trained by
high-fidelity simulation data using finite element-based CFD and informed by a turbulence model, is developed to construct
the full-field pressure from scattered sensor measurements in near real-time. Then, the surrogate pressure model is embedded
in another neural network (NN) for optimizing pressure sensor placement. The goal of the NN-based optimizer is to learn the
best layout of a fixed number of pressure sensors over the structural surface to deliver the most accurate full-field pressure
prediction for various inflow wind conditions.We deploy the model to a representative low-rise building subjected to different
wind conditions. The performance of the proposed framework is assessed by comparing the predicted results with finite
element-based CFD simulation results. The framework shows excellent accuracy and efficiency, which could be potentially
integrated with structural health monitoring to enable digital twins of civil structures.

[Download paper here](http://qimingzhuce.github.io/files/paper1.pdf)
