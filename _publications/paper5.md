---
title: "Machine learning for metal additive manufacturing: predicting temperature andmelt pool fluid dynamics using physics-informed neural networks"
collection: publications
permalink: /publication/paper5
excerpt: 'Physics-Informed Neural Network'
date: 2021-01-06
venue: 'Computational Mechanics'
paperurl: 'http://qimingzhuce.github.io/files/paper5.pdf'
---
The recent explosion of machine learning (ML) and artificial intelligence (AI) shows great potential in the breakthrough
of metal additive manufacturing (AM) process modeling, which is an indispensable step to derive the process-structureproperty
relationship. However, the success of conventional machine learning tools in data science is primarily attributed
to the unprecedented large amount of labeled data-sets (big data), which can be either obtained by experiments or firstprinciple
simulations. Unfortunately, these labeled data-sets are expensive to obtain in AM due to the high expense of the
AM experiments and prohibitive computational cost of high-fidelity simulations, hindering the direct applications of big-data
based ML tools to metal AM problems. To fully exploit the power of machine learning for metal AM while alleviating
the dependence on “big data”, we put forth a physics-informed neural network (PINN) framework that fuses both data and
first physical principles, including conservation laws of momentum, mass, and energy, into the neural network to inform the
learning processes. To the best knowledge of the authors, this is the first application of physics-informed deep learning to three
dimensional AM processes modeling. Besides, we propose a hard-type approach for Dirichlet boundary conditions (BCs)
based on a Heaviside function, which can not only exactly enforce the BCs but also accelerate the learning process. The PINN
framework is applied to two representative metal manufacturing problems, including the 2018 NIST AM-Benchmark test
series.We carefully assess the performance of the PINN model by comparing the predictions with available experimental data
and high-fidelity simulation results, using finite element based variational multi-scale formulation method. The investigations
showthat the PINN, owed to the additional physical knowledge, can accurately predict the temperature and melt pool dynamics
during metal AM processes with only a moderate amount of labeled data-sets. The foray of PINN to metal AM shows the
great potential of physics-informed deep learning for broader applications to advanced manufacturing. All the data-sets and
the PINN code will be made open-sourced in https://yan.cee.illinois.edu/ once the paper is published.

[Download paper here](http://qimingzhuce.github.io/files/paper5.pdf)
