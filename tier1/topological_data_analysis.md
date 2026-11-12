# Topological Data Analysis

A tool the lab uses throughout. Tier 1: Carlsson 2009, Ghrist 2008, plus the
foundational guarantees (the stability theorem) and ML-bridge (vectorization,
Mapper). Tier 2: Edelsbrunner & Harer.

## Reading

- ⭐ **Carlsson (2009)** — *Topology and Data.* Bulletin of the AMS. Launched TDA as a field. Start here for intuition.
- ⭐ **Edelsbrunner & Harer (2010)** — *Computational Topology: An Introduction.* AMS. The textbook. Ch. 1–4 (simplicial complexes) and Ch. 7 (persistence).
- **Ghrist (2008)** — *Barcodes: the persistent topology of data.* Bulletin of the AMS. Beautiful, short introduction to persistence barcodes.
- **Zomorodian & Carlsson (2005)** — *Computing persistent homology.* Discrete & Computational Geometry. The standard persistence algorithm over a field.
- ⭐ **Cohen-Steiner, Edelsbrunner & Harer (2007)** — *Stability of persistence diagrams.* Discrete & Computational Geometry. Persistence diagrams are stable under perturbation (bottleneck distance). The theorem that makes TDA trustworthy.
- **Singh, Mémoli & Carlsson (2007)** — *Topological methods for the analysis of high-dimensional data sets and 3D object recognition.* SPBG / Eurographics. Introduced Mapper, the exploratory TDA visualization.
- **Adams et al. (2017)** — *Persistence images: a stable vector representation of persistent homology.* JMLR. Stable vectorization of diagrams — the bridge to ML.
- **Petri, Expert, Turkheimer, Carhart-Harris, Nutt, Hellyer & Vaccarino (2014)** — *Homological scaffolds of brain functional networks.* J. R. Soc. Interface. Introduced homological scaffolds. Foundational NPLab paper.
- **Petri, Scolamiero, Donato & Vaccarino (2013)** — *Topological strata of weighted complex networks.* PLOS ONE. First persistent-homology on weighted networks.
- ⭐ **Gardner, Hermansen, Pachitariu, Burak, Baas, Dunn, Moser & Moser (2022)** — *Toroidal topology of population activity in grid cells.* Nature 602, 123–128. Persistent homology on recorded neural population activity recovers the torus that grid-cell theory predicts: topology as a test of a circuit model.
- **Giusti, Pastalkova, Curto & Itskov (2015)** — *Clique topology reveals intrinsic geometric structure in neural correlations.* PNAS 112, 13455–13460. Order-invariant topology of correlation matrices: whether neural activity is geometrically organised, without trusting the correlation values.
- **Chaudhuri, Gerçek, Pandey, Peyrache & Fiete (2019)** — *The intrinsic attractor manifold and population dynamics of a canonical cognitive circuit across waking and sleep.* Nature Neuroscience 22, 1512–1520. Recovers a ring manifold from head-direction cell activity without knowing the stimulus, and tracks it across waking and sleep.

## Connection to other topics

- → [Network Neuroscience](../tier2/network_neuroscience.md)
- → [Machine Learning](../tier2/machine_learning.md)

