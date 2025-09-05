---
title: Avoiding Non-Equilibrium Effects in Adaptive Biasing Force Calculations
authors:
- Mengyao Miao
- Haohao Fu
- Hong Zhang
- Xueguang Shao
- Christophe Chipot
- Wensheng Cai
date: '2021-01-01'
publishDate: '2025-09-05T20:10:26.130573Z'
publication_types:
- article-journal
publication: '*Molecular Simulation*'
doi: 10.1080/08927022.2020.1775222
abstract: When using the adaptive biasing force (ABF) algorithm in free-energy calculations,
  unbiased sampling is performed across the transition coordinate to estimate the
  biasing force (F bias). In practice, however, setting the number of molecular dynamics
  steps (N samples) that precede the application of the time-dependent bias is arbitrary.
  In this paper, we find that N samples has a significant effect on the outcome of
  the free-energy calculation. When N samples is too small, marked non-equilibrium
  effects may occur, conducive to slow convergence, or possibly erroneous results.
  This phenomenon is observed in a variety of prototypical cases. Conversely, setting
  arbitrarily N samples to an exaggeratedly large value implies extra computational
  efforts. To avoid possible non-equilibrium artifacts while maintaining computational
  effectiveness, we propose a reliable scheme to make an appropriate choice of N samples
  in ABF-based free-energy calculations, resting on the evolution F bias as a function
  of N samples. Monitoring the latter, a value of N samples that minimises the computational
  cost while guaranteeing convergence of F bias can be determined. This method offers
  a safeguard for reliable free-energy calculations using ABF-based algorithms.
tags:
- Free-energy calculations
- non- equilibrium effects
- time-dependent bias
---
