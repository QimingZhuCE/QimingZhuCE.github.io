---
title: "An immersogeometric formulation for free-surface flows with application to marine engineering problems"
collection: publications
permalink: /publication/paper9
excerpt: 'Finite Element Method'
date: 2019-11-29
venue: 'Computer Methods in Applied Mechanics and Engineering'
paperurl: 'http://qimingzhuce.github.io/files/paper9.pdf'
---
An immersogeometric formulation is proposed to simulate free-surface flows around structures with complex geometry. The
fluid–fluid interface (air–water interface) is handled by the level set method, while the fluid–structure interface is handled
through an immersogeometric approach by immersing structures into non-boundary-fitted meshes and enforcing Dirichlet
boundary conditions weakly. Residual-based variational multiscale method (RBVMS) is employed to stabilize the coupled
Navier–Stokes equations of incompressible flows and level set convection equation. Other level set techniques, including redistancing
and mass balancing, are also incorporated into the immersed formulation. Adaptive quadrature rule is used to
better capture the geometry of the immersed structure boundary by accurately integrating the intersected background elements.
Generalized-α method is adopted for time integration, which results in a two-stage predictor multi-corrector algorithm. GMRES
solver preconditioned with block Jacobian matrices of individual fluid and level set subproblems is used for solving the coupled
linear systems arising from the multi-corrector stage. The capability and accuracy of the proposed method are assessed by
simulating three challenging marine engineering problems, which are a solitary wave impacting a stationary platform, dam break
with an obstacle, and planing of a DTMB 5415 ship model. A refinement study is performed. The predictions of key quantities
of interest by the proposed formulation are in good agreement with experimental results and boundary-fitted simulation results
from others. The proposed formulation has great potential for wide applications in marine engineering problems.

[Download paper here](http://qimingzhuce.github.io/files/paper9.pdf)
