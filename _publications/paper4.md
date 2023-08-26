---
title: "A finite element level set method based on adaptive octree meshes for thermal free-surface flows"
collection: publications
permalink: /publication/paper4
excerpt: 'Finite Element Method'
date: 2021-07-12
venue: 'Computational Mechanics'
paperurl: 'http://qimingzhuce.github.io/files/paper4.pdf'
---
We develop a parallel finite element computational framework based on the level set method and adaptive octree meshes for free-surface flows. The discretized
governing formulations are stabilized using a residual-based variational multiscale method. We redistance the level set field and restore mass conservation
after each time step. The octree mesh is adaptively refined according to the interface location, and the load is rebalanced across processes. The adaptive
octree-based level set method is verified and validated using a canonical problem of dam breakwithout obstacle, and a mesh convergence study is carried
out in this problem. The surface tension is further considered via a continuum surface force model in the method and validated using a problem of single bubble
rising in ambient liquid. A parallel scaling analysis of this method is also performed for the bubble rising problem. The energy equation and Marangoni
effect are finally considered in themethod and validated using a problem of thermocapillary droplet migration with and without gravity. This work illustrates
the ability of the framework to accurately model and predict free-surface flows under various scenarios.

[Download paper here](http://qimingzhuce.github.io/files/paper4.pdf)
