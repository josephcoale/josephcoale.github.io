---
title: "Implicit Methods with Reduced Memory for Thermal Radiative Transfer"

collection: publications

permalink: /publication/3-dya-jmc-mc2021-immr

excerpt: ''

date: October 2021

venue: 'Proceedings of the International Conference on Mathematics and Computational Methods Applied to Nuclear Science and Engineering'

paperurl: 'https://www.ans.org/pubs/proceedings/article-50087/'

preprint_url: 'http://josephcoale.github.io/files/dya-jmc-mc2021-immr.pdf'
---
This paper can be found on the [ANS website](https://www.ans.org/pubs/proceedings/article-50087/)

[Download preprint here](http://josephcoale.github.io/files/jmc-dya-mc2020-immr.pdf)

Abstract:<br/>
This paper presents approximation methods for time-dependent thermal radiative transfer
problems in high energy density physics. It is based on the multilevel quasidiffusion method
defined by the high-order radiative transfer equation (RTE) and the low-order quasidiffusion
(aka VEF) equations for the moments of the specific intensity. A large part of data storage
in TRT problems between time steps is determined by the dimensionality of grid functions
of the radiation intensity. The approximate implicit methods with reduced memory for
the time-dependent Boltzmann equation are applied to the high-order RTE, discretized
in time with the backward Euler (BE) scheme. The high-dimensional intensity from the
previous time level in the BE scheme is approximated by means of the low-rank proper
orthogonal decomposition (POD). Another version of the presented method applies the
POD to the remainder term of P2 expansion of the intensity. The accuracy of the solution of
the approximate implicit methods depends of the rank of the POD. The proposed methods
enable one to reduce storage requirements in time dependent problems. Numerical results
of a Fleck-Cummings TRT test problem are presented.

Recommended citation: D. Y. Anistratov and J. M. Coale, Implicit methods with reduced memory for thermal radiative transfer, in: Proc. of Int. Conf. on Mathematics and Computational Methods Applied to Nuclear Science and Engineering (M&C 2021), Raleigh, NC, 2021. p. 10 pp.
