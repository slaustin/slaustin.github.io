---
title: 'Tackling Hysteresis in Conformational Sampling: How to Be Forgetful with MEMENTO'
authors:
- Simon M. Lichtinger
- Philip C. Biggin
date: '2023-01-01'
publishDate: '2025-09-05T20:10:25.696021Z'
publication_types:
- article-journal
publication: '*Journal of Chemical Theory and Computation*'
doi: 10.1021/acs.jctc.3c00140
abstract: The structure of proteins has long been recognized to hold the key to understanding
  and engineering their function, and rapid advances in structural biology and protein
  structure prediction are now supplying researchers with an ever-increasing wealth
  of structural information. Most of the time, however, structures can only be determined
  in free energy minima, one at a time. While conformational flexibility may thus
  be inferred from static end-state structures, their interconversion mechanisms-a
  central ambition of structural biology-are often beyond the scope of direct experimentation.
  Given the dynamical nature of the processes in question, many studies have attempted
  to explore conformational transitions using molecular dynamics (MD). However, ensuring
  proper convergence and reversibility in the predicted transitions is extremely challenging.
  In particular, a commonly used technique to map out a path from a starting to a
  target conformation called steered MD (SMD) can suffer from starting-state dependence
  (hysteresis) when combined with techniques such as umbrella sampling (US) to compute
  the free energy profile of a transition. Here, we study this problem in detail on
  conformational changes of increasing complexity. We also present a new, history-independent
  approach that we term ``MEMENTO'' (Morphing End states by Modelling Ensembles with
  iNdependent TOpologies) to generate paths that alleviate hysteresis in the construction
  of conformational free energy profiles. MEMENTO utilizes template-based structure
  modelling to restore physically reasonable protein conformations based on coordinate
  interpolation (morphing) as an ensemble of plausible intermediates, from which a
  smooth path is picked. We compare SMD and MEMENTO on well-characterized test cases
  (the toy peptide deca-alanine and the enzyme adenylate kinase) before discussing
  its use in more complicated systems (the kinase P38$α$ and the bacterial leucine
  transporter LeuT). Our work shows that for all but the simplest systems SMD paths
  should not in general be used to seed umbrella sampling or related techniques, unless
  the paths are validated by consistent results from biased runs in opposite directions.
  MEMENTO, on the other hand, performs well as a flexible tool to generate intermediate
  structures for umbrella sampling. We also demonstrate that extended end-state sampling
  combined with MEMENTO can aid the discovery of collective variables on a case-by-case
  basis.
---
