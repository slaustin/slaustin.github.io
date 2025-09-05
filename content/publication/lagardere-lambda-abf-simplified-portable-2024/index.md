---
title: 'Lambda-ABF: Simplified, Portable, Accurate, and Cost-Effective Alchemical
  Free-Energy Computation'
authors:
- Louis Lagardère
- Lise Maurin
- Olivier Adjoua
- Krystel El Hage
- Pierre Monmarché
- Jean-Philip Piquemal
- Jérôme Hénin
date: '2024-01-01'
publishDate: '2025-09-05T20:10:25.459872Z'
publication_types:
- article-journal
publication: '*Journal of Chemical Theory and Computation*'
doi: 10.1021/acs.jctc.3c01249
abstract: We introduce the lambda-Adaptive Biasing Force (lambdaABF) method for the
  computation of alchemical free-energy differences. We propose a software implementation
  and showcase it on biomolecular systems. The method arises from coupling multiple-walker
  adaptive biasing force with $łambda$-dynamics. The sampling of the alchemical variable
  is continuous and converges toward a uniform distribution, making manual optimization
  of the $łambda$ schedule unnecessary. Contrary to most other approaches, alchemical
  freeenergy estimates are obtained immediately without any postprocessing. Free diffusion
  of $łambda$ improves orthogonal relaxation compared to fixed-$łambda$ thermodynamic
  integration or free-energy perturbation. Furthermore, multiple walkers provide generic
  orthogonal space coverage with minimal user input and negligible computational overhead.
  We show that our highperformance implementations coupling the Colvars library with
  NAMD and Tinker-HP can address real-world cases including ligand-receptor binding
  with both fixed-charge and polarizable models, with a demonstrably richer sampling
  than fixed-$łambda$ methods. The implementation is fully open-source, publicly available,
  and readily usable by practitioners of current alchemical methods. Thanks to the
  portable Colvars library, lambda-ABF presents a unified user interface regardless
  of the back-end (NAMD, Tinker-HP, or any software to be interfaced in the future),
  sparing users the effort of learning multiple interfaces. Finally, the Colvars Dashboard
  extension of the visual molecular dynamics (VMD) software provides an interactive
  monitoring and diagnostic tool for lambda-ABF simulations.
---
