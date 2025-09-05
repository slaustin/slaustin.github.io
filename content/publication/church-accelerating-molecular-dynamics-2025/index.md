---
title: Accelerating Molecular Dynamics through Informed Resetting
authors:
- Jonathan R. Church
- Ofir Blumer
- Tommer D. Keidar
- Leo Ploutno
- Shlomi Reuveni
- Barak Hirshberg
date: '2025-01-01'
publishDate: '2025-09-05T20:10:23.676661Z'
publication_types:
- article-journal
publication: '*Journal of Chemical Theory and Computation*'
doi: 10.1021/acs.jctc.4c01238
abstract: We present a procedure for enhanced sampling of molecular dynamics simulations
  through informed stochastic resetting. Many phenomena, such as protein folding and
  crystal nucleation, occur over time scales inaccessible in standard simulations.
  We recently showed that stochastic resetting can accelerate molecular simulations
  that exhibit broad transition time distributions. However, standard stochastic resetting
  does not exploit any information about the reaction progress. For a model system
  and chignolin in explicit water, we demonstrate that an informed resetting protocol
  leads to greater accelerations than standard stochastic resetting in molecular dynamics
  and Metadynamics simulations. This is achieved by resetting only when a certain
  condition is met, e.g., when the distance from the target along the reaction coordinate
  is larger than some threshold. We use these accelerated simulations to infer important
  kinetic observables such as the unbiased mean first-passage time and direct transit
  time. For the latter, Metadynamics with informed resetting leads to speedups of
  2--3 orders of magnitude over unbiased simulations with relative errors of only
  $∼$35--70%. Our work significantly extends the applicability of stochastic resetting
  for enhanced sampling of molecular simulations.
---
