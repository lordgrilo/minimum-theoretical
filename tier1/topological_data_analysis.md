# Topological Data Analysis

A tool the lab uses throughout. Tier 1: Carlsson 2009, Ghrist 2008, plus the
foundational guarantees (the stability theorem) and ML-bridge (vectorization,
Mapper). Tier 2: Edelsbrunner & Harer.

## Reading

- ⭐ **Carlsson (2009)** — *Topology and Data.* Bulletin of the AMS. Launched TDA as a field. Start here for intuition. [doi:10.1090/s0273-0979-09-01249-x](https://doi.org/10.1090/s0273-0979-09-01249-x)
- ⭐ **Edelsbrunner & Harer (2010)** — *Computational Topology: An Introduction.* AMS. The textbook. Ch. 1–4 (simplicial complexes) and Ch. 7 (persistence). [doi:10.1090/mbk/069](https://doi.org/10.1090/mbk/069)
- **Ghrist (2008)** — *Barcodes: the persistent topology of data.* Bulletin of the AMS. Beautiful, short introduction to persistence barcodes. [doi:10.1090/s0273-0979-07-01191-3](https://doi.org/10.1090/s0273-0979-07-01191-3)
- **Zomorodian & Carlsson (2005)** — *Computing persistent homology.* Discrete & Computational Geometry. The standard persistence algorithm over a field. [doi:10.1007/s00454-004-1146-y](https://doi.org/10.1007/s00454-004-1146-y)
- ⭐ **Cohen-Steiner, Edelsbrunner & Harer (2007)** — *Stability of persistence diagrams.* Discrete & Computational Geometry. Persistence diagrams are stable under perturbation (bottleneck distance). The theorem that makes TDA trustworthy. [doi:10.1007/s00454-006-1276-5](https://doi.org/10.1007/s00454-006-1276-5)
- **Singh, Mémoli & Carlsson (2007)** — *Topological methods for the analysis of high-dimensional data sets and 3D object recognition.* SPBG / Eurographics. Introduced Mapper, the exploratory TDA visualization. [doi:10.2312/spbg/spbg07/091-100](https://doi.org/10.2312/spbg/spbg07/091-100)
- **Adams et al. (2017)** — *Persistence images: a stable vector representation of persistent homology.* JMLR. Stable vectorization of diagrams — the bridge to ML. [link](https://jmlr.org/papers/v18/16-337.html)
- **Petri, Expert, Turkheimer, Carhart-Harris, Nutt, Hellyer & Vaccarino (2014)** — *Homological scaffolds of brain functional networks.* J. R. Soc. Interface. Introduced homological scaffolds. Foundational NPLab paper. [doi:10.1098/rsif.2014.0873](https://doi.org/10.1098/rsif.2014.0873)
- **Petri, Scolamiero, Donato & Vaccarino (2013)** — *Topological strata of weighted complex networks.* PLOS ONE. First persistent-homology on weighted networks. [doi:10.1371/journal.pone.0066506](https://doi.org/10.1371/journal.pone.0066506)
- ⭐ **Gardner, Hermansen, Pachitariu, Burak, Baas, Dunn, Moser & Moser (2022)** — *Toroidal topology of population activity in grid cells.* Nature 602, 123–128. Persistent homology on recorded neural population activity recovers the torus that grid-cell theory predicts: topology as a test of a circuit model. [doi:10.1038/s41586-021-04268-7](https://doi.org/10.1038/s41586-021-04268-7)
- **Giusti, Pastalkova, Curto & Itskov (2015)** — *Clique topology reveals intrinsic geometric structure in neural correlations.* PNAS 112, 13455–13460. Order-invariant topology of correlation matrices: whether neural activity is geometrically organised, without trusting the correlation values. [doi:10.1073/pnas.1506407112](https://doi.org/10.1073/pnas.1506407112)
- **Chaudhuri, Gerçek, Pandey, Peyrache & Fiete (2019)** — *The intrinsic attractor manifold and population dynamics of a canonical cognitive circuit across waking and sleep.* Nature Neuroscience 22, 1512–1520. Recovers a ring manifold from head-direction cell activity without knowing the stimulus, and tracks it across waking and sleep. [doi:10.1038/s41593-019-0460-x](https://doi.org/10.1038/s41593-019-0460-x)

## Connection to other topics

- → [Network Neuroscience](../tier2/network_neuroscience.md)
- → [Machine Learning](../tier2/machine_learning.md)

