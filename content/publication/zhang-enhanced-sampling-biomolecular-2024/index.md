---
title: Enhanced Sampling of Biomolecular Slow Conformational Transitions Using Adaptive
  Sampling and Machine Learning
authors:
- Mingyuan Zhang
- Hao Wu
- Yong Wang
date: '2024-01-01'
publishDate: '2025-09-05T20:10:27.790235Z'
publication_types:
- article-journal
publication: '*Journal of Chemical Theory and Computation*'
doi: 10.1021/acs.jctc.4c00764
abstract: "Biomolecular simulations often suffer from the ``time scale problem'',
  hindering the study of rare events occurring over extended time scales. Enhanced
  sampling techniques aim to alleviate this issue by accelerating conformational transitions,
  yet they typically necessitate well-defined collective variables (CVs), posing a
  significant challenge. Machine learning offers promising solutions but typically
  requires rich training data encompassing the entire free energy surface (FES). In
  this work, we introduce an automated iterative pipeline designed to mitigate these
  limitations. Our protocol first utilizes a CV-free count-based adaptive sampling
  method to generate a data set rich in rare events. From this data set, slow modes
  are identified using Koopman-reweighted time-lagged independent component analysis
  (KTICA), which are subsequently leveraged by on-the-fly probability enhanced sampling
  (OPES) to efficiently explore the FES. The effectiveness of our pipeline is demonstrated
  and further compared with the common Markov State Model (MSM) approach on two model
  systems with increasing complexity: alanine dipeptide (Ala2) and deca-alanine (Ala10),
  underscoring its applicability across diverse biomolecular simulations."
---
