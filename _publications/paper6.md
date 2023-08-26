---
title: "A mixed interface-capturing/interface-tracking formulation for thermal multi-phase flows with emphasis on metal additive manufacturing processes"
collection: publications
permalink: /publication/paper6
excerpt: 'Finite Element Method'
date: 2021-05-18
venue: 'Computer Methods in Applied Mechanics and Engineering'
paperurl: 'http://qimingzhuce.github.io/files/paper6.pdf'
---
High fidelity thermal multi-phase flow simulations are in much demand to reveal the multi-scale and multi-physics
phenomena in metal additive manufacturing (AM) processes, yet accurate and robust predictions remain challenging. In this
paper, we present a novel computational framework by mixing interface-capturing/interface-tracking methods for simulating
the thermal multi-phase flows in metal AM applications, focusing on better handling the gas-metal interface, where AM
physics, such as phase transitions and laser-material interactions, mainly takes place. The framework, built on level set method
and variational multi-scale formulation (VMS), features three major contributions: (1) a simple computational geometry-based
re-initialization approach, which maintains excellent signed distance property on unstructured meshes, re-constructs an explicit
representation of gas-metal interface from the level set, and facilitates the treatment of the multiple laser reflections during
keyhole evolution in AM processes; (2) a fully coupled VMS formulation for thermal multi-phase governing equations, including
Navier-Stokes, level set convection, and thermodynamics with melting, solidification, evaporation, and interfacial force models;
and (3) a three-level recursive preconditioning technique to enhance the robustness of linear solvers. We first compare the
geometry-based re-initialization with the Eikonal partial differential equation (PDE)-based approach on two benchmark problems
on level set convection and bubble dynamics. The comparison shows the geometry-based approach attains equivalent and even
better performance on key criteria than the PDE-based counterpart. We then apply the developed framework to simulate two
AM experiments, which Argonne National Laboratory has recently conducted using in-situ high-speed, high-energy x-ray
imaging. The proposed framework’s accuracy is assessed by thoroughly comparing the simulated results against experimental
measurements on various quantities. We also report important quantities that experiments cannot measure to show the modeling
capability.

[Download paper here](http://qimingzhuce.github.io/files/paper6.pdf)
