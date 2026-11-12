# Computational Tools & Environment

## Languages

- **Python** — Primary language for everything. No exceptions for new lab members unless there's a compelling reason.
- **Julia** — Acceptable for performance-critical numerical work. Agree it with your supervisor before committing a project to Julia.

## Core Scientific Stack

| Library | Purpose | When to use |
|---------|---------|-------------|
| NumPy | Array operations, linear algebra | Always |
| SciPy | Optimization, integration, sparse matrices, signal processing | Most projects |
| Pandas | Tabular data manipulation | Data cleaning, preprocessing |
| Matplotlib | Publication-quality figures | Always |
| Seaborn | Statistical visualizations | Exploratory analysis |

## Network Science

| Library | Purpose | When to use |
|---------|---------|-------------|
| NetworkX | Graph creation, algorithms, prototyping | Small-medium networks, exploration |
| graph-tool | Fast graph algorithms, Bayesian SBM inference | Large networks, serious inference |
| igraph | Fast graph algorithms | When NetworkX is too slow and graph-tool is overkill |
| HyperNetX | Hypergraph analysis | Higher-order network projects |
| XGI | Comple**x** **G**roup **I**nteractions — hypergraphs and simplicial complexes | Higher-order projects (newer, actively developed) |

## Topological Data Analysis

| Library | Purpose | When to use |
|---------|---------|-------------|
| GUDHI | Persistent homology, simplicial complexes, alpha/Rips complexes | Primary TDA tool |
| Ripser / ripser.py | Fast Rips persistent homology | Large point clouds |
| giotto-tda | Scikit-learn compatible TDA pipeline | ML + TDA integration |
| dionysus2 | Persistent homology with cohomology | When you need specific cohomology features |

## Machine Learning

| Library | Purpose | When to use |
|---------|---------|-------------|
| PyTorch | Deep learning, neural networks | Primary DL framework |
| PyTorch Geometric | GNNs, simplicial neural networks | Graph/simplicial ML |
| scikit-learn | Classical ML, preprocessing, evaluation | Baselines, pipelines, clustering |
| JAX | Differentiable programming, GPU-accelerated numerics | When you need autodiff outside DL |

## Information Theory

| Library | Purpose | When to use |
|---------|---------|-------------|
| dit | Discrete information theory (entropy, MI, PID, O-information) | Information-theoretic analysis |
| JIDT | Java Information Dynamics Toolkit (transfer entropy, active information) | Time series info theory |
| IDTxl | Information dynamics toolkit (Python, multivariate TE) | Neural data, causal inference |
| POT | Python Optimal Transport | OT computations, Wasserstein distances |

## Neuroscience

| Library | Purpose | When to use |
|---------|---------|-------------|
| nilearn | fMRI data analysis, brain parcellations | Neuroimaging projects |
| MNE-Python | EEG/MEG analysis | Electrophysiology projects |
| brainspace | Gradient analysis, brain visualization | Connectomics |
| nibabel | Neuroimaging file I/O | Reading/writing NIfTI, GIFTI files |

## Development Practices

- **Version control:** Git, always. GitHub for collaboration. No exceptions.
- **Environment management:** Conda or pip virtual environments. Never install globally.
- **Notebooks vs. scripts:** Jupyter for exploration and prototyping. Scripts (.py) for anything that runs in a pipeline or will be reused. Don't submit a paper with results generated only in notebooks — the final analysis should be reproducible from scripts.
- **Documentation:** Docstrings for functions. README for every project repo. Comments for anything non-obvious.
- **Code review:** Before submission, have at least one other lab member read your analysis code.

## Compute Resources

- University cluster access — ask your supervisor for setup
- Personal machines for development
- Cloud (AWS/GCP) for large-scale jobs — agree the budget with your supervisor before spinning up instances
