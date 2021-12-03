---
title: "Laplacian 2D Finite Difference (FD) solver on Stampede2 Supercomputer"
layout: archive
sitemap: true
author_profile: true
permalink: /TNT/
---

|![stampede2.jpeg](/assets/images/stampede2.jpeg)
|:--:|
| Stampede2 Supercomputer. Ranked 44th on list of fastest supercomputers in the world as per November 2021. Courtesy Texas Advanced Computing Center, TACC. |

We created a steady-state heat equation solver using Object Oriented Programming in C++. The goal of the project was to use rigorous coding practices to create the solver. We leveraged TACC's Stampede2 Supercomputer and the SLURM workload manager for our needs. The highlights of the project include:

- Gauss, Jacobi, PETSc solvers for steady state heat solvers
- Code builds using Autotools
- Use of SLURM environment
- HDF5 storage format
- GRVY parser and logger
- MASA for code verification
- Github for version control
- Object Oriented Programming
- Testing using bats
- Continuous Integration using Travis CI and Docker
- 0% memory errors (Valgrind)
- 98% code coverage tested using lcov and gcov

