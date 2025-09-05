---
title: 'ELF: An Extended-Lagrangian Free Energy Calculation Module for Multiple Molecular
  Dynamics Engines'
authors:
- Haochuan Chen
- Haohao Fu
- Xueguang Shao
- Christophe Chipot
- Wensheng Cai
date: '2018-01-01'
publishDate: '2025-09-05T20:10:23.583635Z'
publication_types:
- article-journal
publication: '*Journal of Chemical Information and Modeling*'
doi: 10.1021/acs.jcim.8b00115
abstract: Extended adaptive biasing force (eABF), a collective variable (CV)-based
  importance-sampling algorithm, has proven to be very robust and efficient compared
  with the original ABF algorithm. Its implementation in Colvars, a software addition
  to molecular dynamics (MD) engines, is, however, currently limited to NAMD and LAMMPS.
  To broaden the scope of eABF and its variants, like its generalized form (egABF),
  and make them available to other MD engines, e.g., GROMACS, AMBER, CP2K, and openMM,
  we present a PLUMED-based implementation, called extended-Lagrangian free energy
  calculation (ELF). This implementation can be used as a stand-alone gradient estimator
  for other CV-based sampling algorithms, such as temperature-accelerated MD (TAMD)
  and extended-Lagrangian metadynamics (MtD). ELF provides the end user with a convenient
  framework to help select the best-suited importance-sampling algorithm for a given
  application without any commitment to a particular MD engine.
---
