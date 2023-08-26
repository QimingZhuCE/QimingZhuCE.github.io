---
title: "Computational multi-phase convective conjugate heat transfer on overlapping meshes: a quasi-direct coupling approach via Schwarz alternatingmethod"
collection: publications
permalink: /publication/paper3
excerpt: 'Finite Element Method'
date: 2022-08-09
venue: 'Computational Mechanics'
paperurl: 'http://qimingzhuce.github.io/files/paper3.pdf'
---
We present a new computational framework to simulate the multi-phase convective conjugate heat transfer (CHT) problems
emanating from realistic manufacturing processes. The paper aims to address the challenges of boundary-fitted and immersed
boundary approaches, which cannot simultaneously achieve fluid-solid interface accuracy and geometry-flexibility in simulating
this class of multi-physics systems. The method development is built on a stabilized Arbitrary Lagrangian-Eulerian
(ALE)-based finite element thermal multi-phase formulation, which is discretized by overlapping one boundary-fitted mesh
and non-boundary-fitted mesh with a quasi-direct coupling approach via Schwarz alternating method. The framework utilizes
a volume-of-fluid (VoF)-based multi-phase flow model coupled with a thermodynamics model with phase transitions
to capture the conjugate heat transfer between the solid and multi-phase flows and the multi-stage boiling and condensation
phenomena. The quasi-direct coupling approach allows the exact and automatic enforcement of temperature and heat-flux
compatibility at the fluid-solid interface with large property discontinuities. From the perspective of method development, the
proposed framework fully exploits boundary-fitted approach’s strength in resolving fluid-solid interface and boundary layers
and immersed boundary approach’s geometry flexibility in handling moving objects while circumventing each individual’s
limitations. From the perspective of industry applications, such as water quenching processes, the resulting model can enable
accurate temperature prediction directly from process parameters without invoking the conventional empirical heat transfer
coefficient (HTC)-based approach that requires intensive calibration. We present themathematical formulation and numerical
implementation in detail and demonstrate the claimed features of the proposed framework through a set of benchmark problems
and real-world water quenching processes. The accuracy of the proposed framework is carefully assessed by comparing
the prediction with other computational results and experimental measurements.

[Download paper here](http://qimingzhuce.github.io/files/paper3.pdf)
