---
title: Extended Adaptive Biasing Force Algorithm. An On-the-Fly Implementation for
  Accurate Free-Energy Calculations
authors:
- Haohao Fu
- Xueguang Shao
- Christophe Chipot
- Wensheng Cai
date: '2016-01-01'
publishDate: '2025-01-20T17:29:37.641995Z'
publication_types:
- article-journal
publication: '*Journal of Chemical Theory and Computation*'
doi: 10.1021/acs.jctc.6b00447
abstract: Proper use of the adaptive biasing force (ABF) algorithm in free-energy
  calculations needs certain prerequisites to be met, namely, that the Jacobian for
  the metric transformation and its first derivative be available and the coarse variables
  be independent and fully decoupled from any holonomic constraint or geometric restraint,
  thereby limiting singularly the field of application of the approach. The extended
  ABF (eABF) algorithm circumvents these intrinsic limitations by applying the time-dependent
  bias onto a fictitious particle coupled to the coarse variable of interest by means
  of a stiff spring. However, with the current implementation of eABF in the popular
  molecular dynamics engine NAMD, a trajectory-based post-treatment is necessary to
  derive the underlying free-energy change. Usually, such a posthoc analysis leads
  to a decrease in the reliability of the free-energy estimates due to the inevitable
  loss of information, as well as to a drop in efficiency, which stems from substantial
  read-write accesses to file systems. We have developed a user-friendly, on-the-fly
  code for performing eABF simulations within NAMD. In the present contribution, this
  code is probed in eight illustrative examples. The performance of the algorithm
  is compared with traditional ABF, on the one hand, and the original eABF implementation
  combined with a posthoc analysis, on the other hand. Our results indicate that the
  on-the-fly eABF algorithm (i) supplies the correct free-energy landscape in those
  critical cases where the coarse variables at play are coupled to either each other
  or to geometric restraints or holonomic constraints, (ii) greatly improves the reliability
  of the free-energy change, compared to the outcome of a posthoc analysis, and (iii)
  represents a negligible additional computational effort compared to regular ABF.
  Moreover, in the proposed implementation, guidelines for choosing two parameters
  of the eABF algorithm, namely the stiffness of the spring and the mass of the fictitious
  particles, are proposed. The present on-the-fly eABF implementation can be viewed
  as the second generation of the ABF algorithm, expected to be widely utilized in
  the theoretical investigation of recognition and association phenomena relevant
  to physics, chemistry, and biology.
---
