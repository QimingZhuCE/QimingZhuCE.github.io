---
title: "A moving-domain CFD solver in FEniCS with applications to tidal turbine simulations in turbulent flows"
collection: publications
permalink: /publication/paper7
excerpt: 'Finite Element Method'
date: 2021-01-01
venue: 'Computers & Mathematics with Applications'
paperurl: 'http://qimingzhuce.github.io/files/paper7.pdf'
---
A moving-domain computational fluid dynamics (CFD) solver is designed by deploying
the Arbitrary Lagrangian Eulerian Variational Multi-scale Formulation (ALE-VMS) enhanced
with weak enforcement of essential boundary conditions (weak BC) into the
open-source finite element automation software FEniCS. The mathematical formulation
of ALE-VMS, which is working as a Large Eddy Simulation (LES) model for turbulent
flows, and weak BC, which is acting as a wall model, are presented with the implementation
details in FEniCS. To validate the CFD solver, simulations of flow past a
stationary sphere are performed with moving meshes first. Refinement study shows the
results quickly converge to the reference results with fixed grids. Then, the solver is
utilized to simulate a tidal turbine rotor with uniform and turbulent inflow conditions.
Good agreement is achieved between the computational results and experimental
measurements in terms of thrust and power coefficients for the uniform inflow case. The
effect of the inflow turbulence intensity on the tidal turbine performance is quantified.

[Download paper here](http://qimingzhuce.github.io/files/paper7.pdf)
