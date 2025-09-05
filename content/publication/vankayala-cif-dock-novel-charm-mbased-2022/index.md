---
title: 'CIFDock: A Novel CHARMM-based Flexible Receptor--Flexible Ligand Docking Protocol'
authors:
- Sai L. Vankayala
- Luke C. Warrensford
- Amanda R. Pittman
- Benjamin C. Pollard
- Fiona L. Kearns
- Joseph D. Larkin
- H. Lee Woodcock
date: '2022-01-01'
publishDate: '2025-09-05T20:13:47.554139Z'
publication_types:
- article-journal
publication: '*Journal of Computational Chemistry*'
doi: 10.1002/jcc.26759
abstract: Docking studies play a critical role in the current workflow of drug discovery.
  However, limitations may often arise through factors including inadequate ligand
  sampling, a lack of protein flexibility, scoring function inadequacies (e.g., due
  to metals, co-factors, etc.), and difficulty in retaining explicit water molecules.
  Herein, we present a novel CHARMM-based induced fit docking (CIFDock) workflow that
  can circumvent these limitations by employing all-atom force fields coupled to enhanced
  sampling molecular dynamics procedures. Self-guided Langevin dynamics simulations
  are used to effectively sample relevant ligand conformations, side chain orientations,
  crystal water positions, and active site residue motion. Protein flexibility is
  further enhanced by dynamic sampling of side chain orientations using an expandable
  rotamer library. Steps in the procedure consisting of fixing individual components
  (e.g., the ligand) while sampling the other components (e.g., the residues in the
  active site of the protein) allow for the complex to adapt to conformational changes.
  Ultimately, all components of the complex---the protein, ligand, and waters---are
  sampled simultaneously and unrestrained with SGLD to capture any induced fit effects.
  This modular flexible docking procedure is automated using CHARMM scripting, interfaced
  with SLURM array processing, and parallelized to use the desired number of processors.
  We validated the CIFDock procedure by performing cross-docking studies using a data
  set comprised of 21 pharmaceutically relevant proteins. Five variants of the CHARMM-based
  SWISSDOCK scoring functions were created to quantify the results of the final generated
  poses. Results obtained were comparable to, or in some cases improved upon, commercial
  docking program data.
tags:
- CHARMM
- clustering
- force field
- induced fit docking
- ligand sampling
---
