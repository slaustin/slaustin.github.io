---
title: Overcoming Free-Energy Barriers with a Seamless Combination of a Biasing Force
  and a Collective Variable-Independent Boost Potential
authors:
- Haochuan Chen
- Haohao Fu
- Christophe Chipot
- Xueguang Shao
- Wensheng Cai
date: '2021-01-01'
publishDate: '2025-09-05T20:10:23.604437Z'
publication_types:
- article-journal
publication: '*Journal of Chemical Theory and Computation*'
doi: 10.1021/acs.jctc.1c00103
abstract: Amid collective-variable (CV)-based importance-sampling algorithms, a hybrid
  of the extended adaptive biasing force and the well-tempered metadynamics algorithms
  (WTM-eABF) has proven particularly cost-effective for exploring the rugged free-energy
  landscapes that underlie biological processes. However, as an inherently CV-based
  algorithm, this hybrid scheme does not explicitly accelerate sampling in the space
  orthogonal to the chosen CVs, thereby limiting its efficiency and accuracy, most
  notably in those cases where the slow degrees of freedom of the process at hand
  are not accounted for in the model transition coordinate. Here, inspired by Gaussian-accelerated
  molecular dynamics (GaMD), we introduce the same CV-independent harmonic boost potential
  into WTM-eABF, yielding a hybrid algorithm coined GaWTM-eABF. This algorithm leans
  on WTM-eABF to explore the transition coordinate with a GaMD-mollified potential
  and recovers the unbiased freeenergy landscape through thermodynamic integration
  followed by proper reweighting. As illustrated in our numerical tests, GaWTM-eABF
  effectively overcomes the free-energy barriers in orthogonal space and correctly
  recovers the unbiased potential of mean force (PMF). Furthermore, applying both
  GaWTM-eABF and WTM-eABF to two biologically relevant processes, namely, the reversible
  folding of (i) deca-alanine and (ii) chignolin, our results indicate that GaWTM-eABF
  reduces the uncertainty in the PMF calculation and converges appreciably faster
  than WTM-eABF. Obviating the need of multiple-copy strategies, GaWTM-eABF is a robust,
  computationally efficient algorithm to surmount the free-energy barriers in orthogonal
  space and maps with utmost fidelity the free-energy landscape along selections of
  CVs. Moreover, our strategy that combines WTM-eABF with GaMD can be easily extended
  to other biasing-force algorithms.
---
