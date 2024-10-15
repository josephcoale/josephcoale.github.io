---
title: "A Reduced-Order Model for Nonlinear Radiative Transfer Problems Based on Moment Equations and POD-Petrov-Galerkin Projection of the Normalized Boltzmann Transport Equation"

collection: publications

permalink: /publication/12-jmc-dya-jcp-2023

excerpt: ''

date: July 2024

venue: 'Journal of Computational Physics'

paperurl: 'https://doi.org/10.1016/j.jcp.2024.113044'

arxiv_url: 'https://arxiv.org/abs/2308.15375'
---
DOI: [https://doi.org/10.1016/j.jcp.2024.113044](https://doi.org/10.1016/j.jcp.2024.113044)

Find the preprint on [Arxiv.org](https://arxiv.org/abs/2308.15375)

Abstract:<br/>
A data-driven projection-based reduced-order model (ROM) for nonlinear thermal radiative transfer (TRT) problems is presented. The TRT ROM is formulated by (i) a hierarchy of low-order quasidiffusion (aka variable Eddington factor) equations for moments of the radiation intensity and (ii) the normalized Boltzmann transport equation (BTE). The multilevel system of moment equations is derived by projection of the BTE onto a sequence of subspaces which represent elements of the phase space of the problem. Exact closure for the moment equations is provided by the Eddington tensor. A Petrov-Galerkin (PG) projection of the normalized BTE is formulated using a proper orthogonal decomposition (POD) basis representing the normalized radiation intensity over the whole phase space and time. The Eddington tensor linearly depends on the solution of the normalized BTE. By linear superposition of the POD basis functions, a low-rank expansion of the Eddington tensor is constructed with coefficients defined by the PG projected normalized BTE. The material energy balance (MEB) equation is coupled with the effective grey low-order equations which exist on the same dimensional scale as the MEB equation. The resulting TRT ROM is structure and asymptotic preserving. A detailed analysis of the ROM is performed on the classical Fleck-Cummings (F-C) TRT multigroup test problem in 2D geometry. Numerical results are presented to demonstrate the ROM's effectiveness in the simulation of radiation wave phenomena. The ROM is shown to produce solutions with sufficiently high accuracy while using low-rank approximation of the normalized BTE solution. Essential physical characteristics of supersonic radiation wave are preserved in the ROM solutions.

Recommended citation: J. M. Coale and D. Y. Anistratov, A Reduced-Order Model for Nonlinear Radiative Transfer Problems Based on Moment Equations and POD-Petrov-Galerkin Projection of the Normalized Boltzmann Transport Equation, Journal of Computational Physics 509 (2024) 113044.
