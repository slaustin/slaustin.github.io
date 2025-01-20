---
title: Comprehensive Approach to Simulating Large Scale Conformational Changes in
  Biological Systems Utilizing a Path Collective Variable and New Barrier Restraint
authors:
- István Kolossváry
- Woody Sherman
date: '2023-01-01'
publishDate: '2025-01-20T17:29:37.730408Z'
publication_types:
- article-journal
publication: '*J. Phys. Chem. B*'
doi: 10.1021/acs.jpcb.3c02028
abstract: 'Conformational sampling of complex biomolecules is an emerging frontier
  in drug discovery. Advances in lab-based structural biology and related computational
  approaches like AlphaFold have made great strides in obtaining static protein structures
  for biologically relevant targets. However, biology is in constant motion, and many
  important biological processes rely on conformationally driven events. Conventional
  molecular dynamics (MD) simulations run on standard hardware are impractical for
  many drug design projects, where conformationally driven biological events can take
  microseconds to milliseconds or longer. An alternative approach is to focus the
  search on a limited region of conformational space defined by a putative reaction
  coordinate (i.e., path collective variable). The search space is typically limited
  by applying restraints, which can be guided by insights about the underlying biological
  process of interest. The challenge is striking a balance between the degree to which
  the system is constrained and still allowing for natural motions along the path.
  A plethora of restraints exist to limit the size of conformational search space,
  although each has drawbacks when simulating complex biological motions. In this
  work, we present a three-stage procedure to construct realistic path collective
  variables (PCVs) and introduce a new kind of barrier restraint that is particularly
  well suited for complex conformationally driven biological events, such as allosteric
  modulations and conformational signaling. The PCV presented here is all-atom (as
  opposed to C-alpha or backbone only) and is derived from all-atom MD trajectory
  frames. The new restraint relies on a barrier function (specifically, the scaled
  reciprocal function), which we show is particularly beneficial in the context of
  molecular dynamics, where near-hard-wall restraints are needed with zero tolerance
  to restraint violation. We have implemented our PCV and barrier restraint within
  a hybrid sampling framework that combines well-tempered metadynamics and extended-Lagrangian
  adaptive biasing force (meta-eABF). We use three particular examples of high pharmaceutical
  interest to demonstrate the value of this approach: (1) sampling the distance from
  ubiquitin to a protein of interest within the supramolecular cullin--RING ligase
  complex, (2) stabilizing the wild-type conformation of the oncogenic mutant JAK2-V617F
  pseudokinase domain, and (3) inducing an activated state of the stimulator of interferon
  genes (STING) protein observed upon ligand binding. For examples 2 and 3, we present
  statistical analysis of meta-eABF free energy estimates and, for each case, code
  for reproducing this work.'
---
