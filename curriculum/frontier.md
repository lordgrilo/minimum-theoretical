# Tier 3 · The Frontier

The lab's open questions, each built on one stream: what is unsettled, readings past the stream (including the strongest rival account), and the lab claim your capstone can try to break. Optional, except the one you choose for your capstone.

## When do data reveal higher-order structure?

_Builds on: Higher-order networks._

When observations come from group records or from dynamics, when do the data identify the order of the interactions, and when do several structures explain them equally well?

**What is unsettled.** Reconstruction methods usually return one best structure, but structure and dynamics can trade off along families of equally good explanations, and low-rank dynamics may hide structure in principle. Higher-order statistics can also come from pairwise mechanisms. Whether description length, held-out prediction or perturbation experiments can settle the order is open.

**The lab claim to test.** Ordinary pairwise network data can hide higher-order interactions, and a parsimonious Bayesian reconstruction recovers them, adding a group only when the evidence supports it. Source: Young, Petri & Peixoto (2021), *Hypergraph reconstruction from network data.* Communications Physics.

### Readings past the stream

- **Rival account.** Rosas, Mediano, Luppi, Varley, Lizier, Stramaglia, Jensen & Marinazzo (2022), *Disentangling high-order mechanisms and high-order behaviours in complex systems.* Nature Physics 18, 476–477.
  The strongest competing account: higher-order behaviour can come from pairwise mechanisms, so a higher-order signature is not yet a higher-order interaction.
- Malizia, Corso, Gambuzza, Russo, Latora & Frasca (2024), *Reconstructing higher-order interactions in coupled dynamical systems.* Nature Communications 15, 5184.
  Reconstruction from dynamics rather than from group records: the other half of the identifiability question.
- Prasse & Van Mieghem (2022), *Predicting network dynamics without requiring the knowledge of the interaction graph.* PNAS 119, e2205517119.
  If dynamics can be predicted without the graph, say what reconstruction buys that prediction does not.
- Thibeault, Allard & Desrosiers (2024), *The low-rank hypothesis of complex systems.* Nature Physics 20, 294–302.
  Low-rank dynamics are one reason different structures can produce the same behaviour.
- Robiglio, Neri, Iacopini, Petri & Barrat (2024), *Synergistic signatures of group mechanisms in higher-order systems.*
  Lab paper: when synergy in the data points to a group mechanism, and when it does not.

**Capstone.** Take one published reconstruction of higher-order structure and show whether a pairwise or latent-variable model, or a different structure, explains the same data at equal description length or held-out likelihood.

## Do higher-order brain signatures add information?

_Builds on: Brain and clinical neuroscience._

Synergy, irreducible dependence and topological scaffolds separate people, states and patients. Do they carry information that pairwise connectivity does not, once reliability and confounds are matched?

**What is unsettled.** Many higher-order measures are computed from the same signals as pairwise connectivity, so whether they add information or redescribe it is not settled. A more reliable measure also looks more distinctive, and more heritable, whatever it encodes. And pairwise maximum-entropy models already reproduce much of the structure of small neural populations.

**The lab claim to test.** Instantaneous higher-order co-fluctuations separate dynamical regimes that pairwise statistics cannot, and leave measurable signatures in brain activity. Source: Santoro, Battiston, Petri & Amico (2023), *Higher-order organization of multivariate time series.* Nature Physics.

### Readings past the stream

- **Rival account.** Schneidman, Berry, Segev & Bialek (2006), *Weak pairwise correlations imply strongly correlated network states in a neural population.* Nature 440, 1007–1012.
  The strongest competing account: pairwise models capture most of a population's correlated states, so higher order has to earn its place.
- Ganmor, Segev & Schneidman (2011), *Sparse low-order interaction network underlies a highly correlated and learnable neural population code.* PNAS 108, 9679–9684.
  Where pairs stop being enough: larger populations need a sparse set of low-order interactions.
- Finn, Shen, Scheinost, Rosenberg, Huang, Chun, Papademetris & Constable (2015), *Functional connectome fingerprinting: identifying individuals using patterns of brain connectivity.* Nature Neuroscience 18, 1664–1671.
  The pairwise fingerprinting baseline that a higher-order fingerprint has to beat.
- Noble, Scheinost & Constable (2019), *A decade of test-retest reliability of functional connectivity: a systematic review and meta-analysis.* NeuroImage 203, 116157.
  Reliability limits every comparison: a measure that is merely more reliable will look more distinctive.

**Capstone.** Take one published higher-order brain result and test whether pairwise connectivity with matched reliability, or a pairwise maximum-entropy model, reproduces it.

## Where do capacity limits come from?

_Builds on: Cognition, semanticity and NeuroAI._

Generalization needs shared representations, and sharing causes interference. Does that cost, under finite precision, explain the capacity limits seen in people, animals and networks better than accounts based on resources or slots?

**What is unsettled.** The semantic-horizon account predicts a non-monotonic generalization curve and a ceiling of a few bits. Resource models, in which precision is spread more thinly as load grows, slot models with a fixed number of items, and control accounts based on interference each fit parts of the same data. Which observation separates them, and whether precision itself falls with load, is open.

**The lab claim to test.** Capacity limits reflect the curse of generalization: the shared representations that support generalization also cause interference, and with any decision noise identification is capped at a few bits. Source: Frankland, Marjieh, Nurisso et al. (2025), *Capacity limits in cognitive processing reflect the curse of generalization.* Psychological Review (accepted, 2026).

### Readings past the stream

- **Rival account.** Ma, Husain & Bays (2014), *Changing concepts of working memory.* Nature Neuroscience 17, 347–356.
  The strongest competing account: no fixed limit, only a resource spread across items.
- Cowan (2001), *The magical number 4 in short-term memory: a reconsideration of mental storage capacity.* Behavioral and Brain Sciences 24, 87–114.
  The case for a fixed item limit, and the evidence a ceiling of a few bits has to reproduce.
- Sims (2018), *Efficient coding explains the universal law of generalization in human perception.* Science 360, 652–656.
  Shepard's law from efficient coding: the nearest rival derivation of the generalization gradient.
- Musslick & Cohen (2021), *Rationalizing constraints on the capacity for cognitive control.* Trends in Cognitive Sciences 25, 757–775.
  Interference between shared representations as the reason control is limited: the account closest to ours.

**Capstone.** Fit the semantic-horizon model, a resource model and a slot model to one capacity dataset with matched free parameters, and name the observation that separates them.

## Does representational geometry predict where models fail?

_Builds on: Cognition, semanticity and NeuroAI._

In language and vision–language models, does the geometry of internal representations predict where binding, composition and generalization fail, and do models align with brains for the same reasons?

**What is unsettled.** Concept directions can be found and steered, but superposition and non-linear features complicate a purely linear picture. Convergence across models may reflect shared data rather than shared computation. And high alignment with brain data does not show that a model computes the way the brain does.

**The lab claim to test.** In vision–language models, the geometric overlap between concept vectors predicts error patterns such as hallucinated objects and confused similarity judgements. Source: Savietto, Campbell, Panisson, Nurisso, Petri, Cohen & Perotti (2026), *The geometry of representational failures in vision-language models.* ICML 2026 (accepted). arXiv:2602.07025.

### Readings past the stream

- **Rival account.** Bowers, Malhotra, Dujmović, Llera Montero, Tsvetkov, Biscione, Puebla, Adolfi, Hummel, Heaton, Evans, Mitchell & Blything (2023), *Deep problems with neural network models of human vision.* Behavioral and Brain Sciences 46, e385.
  The strongest competing account: success on benchmarks and on brain prediction says little about whether a model works like the brain.
- Park, Choe & Veitch (2024), *The linear representation hypothesis and the geometry of large language models.* ICML 2024. arXiv:2311.03658
  What it means, formally, for a concept to be a direction, and which geometry that implies.
- Campbell, Rane, Giallanza, De Sabbata, Ghods, Joshi, Ku, Frankland, Griffiths, Cohen & Webb (2024), *Understanding the limits of vision language models through the lens of the binding problem.* NeurIPS 2024. arXiv:2411.00238
  The behavioural side: multi-object failures in vision–language models behave like the binding problem.
- Chung, Lee & Sompolinsky (2018), *Classification and geometry of general perceptual manifolds.* Physical Review X.
  Links the geometry of representations to how many categories a linear readout can separate.
- Huh, Cheung, Wang & Isola (2024), *Position: The Platonic representation hypothesis.* ICML 2024. arXiv:2405.07987
  The claim that models converge on one representation, and what would have to be true for that to mean shared computation.

**Capstone.** Take one published claim that a model represents a concept, and test whether the same geometry appears in a model that fails the behavioural test.

## What carries information in sperm-whale codas?

_Builds on: Social, collective and animal communication · Animal communication._

Codas vary in rhythm, tempo and ornamentation, and with context. Which of these variations carry information for the whales, and what evidence would show it?

**What is unsettled.** Combinatorial structure in codas is documented, but whether the whales use it compositionally, as identity and clan markers, or as a reflection of context is open. Repertoire claims depend on how codas are detected and annotated, and without playback experiments meaning can only be inferred from context.

**The lab claim to test.** Sperm-whale communication can be decoded by combining large, context-rich recordings with machine learning, then testing hypotheses with playback. Source: Andreas, Beguš, Bronstein, Diamant, Delaney et al. (2022), *Toward understanding the communication in sperm whales.* iScience.

### Readings past the stream

- **Rival account.** Hersh et al. (2022), *Evidence from sperm whale clans of symbolic marking in non-human cultures.* PNAS 119, e2201692119.
  The strongest competing account: coda variation marks identity and clan, which is information, but not a message.
- Sainburg, Thielk & Gentner (2020), *Finding, visualizing, and quantifying latent structure across diverse animal vocal repertoires.* PLoS Computational Biology.
  How latent structure is found in vocal repertoires, and what the method assumes.
- Arnon, Kirby, Allen, Garrigue, Carroll & Garland (2025), *Whale song shows language-like statistical structure.* Science 387, 649–653.
  Language-like statistics in humpback song, and why statistics alone do not show meaning.
- Hauser, Chomsky & Fitch (2002), *The faculty of language: what is it, who has it, and how did it evolve?* Science.
  The bar a claim of language has to clear, as its sceptics set it.

**Capstone.** Take one published claim about coda structure and test it against a null that preserves individual and clan identity cues; name the observation, or the playback, that would show the whales use that structure.

## Do real contagions need groups?

_Builds on: Social, collective and animal communication · Social coordination._

Group reinforcement predicts sudden transitions and hysteresis in the spread of behaviour. Can observational data show that a real contagion is higher-order, rather than pairwise and complex, or driven by homophily?

**What is unsettled.** In observational data, complex contagion, homophily and shared exposure leave similar traces, and few experiments manipulate group structure directly. Methods that tell simple from complex contagion exist; whether they can identify group reinforcement is open.

**The lab claim to test.** Group reinforcement makes social contagion bistable, with discontinuous transitions that pairwise models do not produce. Source: Iacopini, Petri, Barrat & Latora (2019), *Simplicial models of social contagion.* Nature Communications.

### Readings past the stream

- **Rival account.** Shalizi & Thomas (2011), *Homophily and contagion are generically confounded in observational social network studies.* Sociological Methods & Research 40, 211–239.
  The strongest competing account: in observational data, homophily can mimic contagion, so a spreading pattern alone proves little.
- Centola (2010), *The spread of behavior in an online social network experiment.* Science 329, 1194–1197.
  The experimental evidence for complex contagion, and what it does and does not show about groups.
- Cencetti, Contreras, Mancastroppa & Barrat (2023), *Distinguishing simple and complex contagion processes on networks.* Physical Review Letters 130, 247401.
  A test that tells simple from complex contagion from the infection sequence: a starting point for testing group reinforcement.
- St-Onge, Iacopini, Latora, Barrat, Petri, Allard & Hébert-Dufresne (2022), *Influential groups for seeding and sustaining nonlinear contagion in heterogeneous hypergraphs.* Communications Physics 5, 25.
  Lab paper: which groups seed and sustain nonlinear contagion, and so where to look in data.

**Capstone.** Take one dataset of adoptions or spreading behaviour, fit simple, pairwise complex and group contagion models, and show which the data can tell apart once homophily is controlled.

## Is there a privileged scale?

_Builds on: Renormalization and criticality._

Coarse-graining can make dynamics more predictable while making structure harder to reconstruct. Is there a scale at which a system is best described, and does it agree across dynamics, information and structure?

**What is unsettled.** Causal-emergence measures pick out a macroscale, but which one depends on how states are grouped and on the measure. Renormalization schemes preserve different things (diffusion, geometry, spectra) and can disagree about the scale. Whether a dynamics-preserving map exists at a given scale can be checked only for some schemes.

**The lab claim to test.** Harmonic morphisms are the minimal condition under which random walks on a network project exactly onto random walks on its coarse-grained image, and the harmonic degree measures how close any coarse-graining comes. Source: Guadagnuolo, Nurisso, Galluzzi, Allard & Petri (2026), *Harmonic morphisms and dynamical invariants in network renormalization.* arXiv:2604.08386 (under review, PRX).

### Readings past the stream

- **Rival account.** Eberhardt & Lee (2022), *Causal emergence: when distortions in a map obscure the territory.* Philosophies 7, 30.
  The strongest competing account: a measure that finds a better macroscale may be rewarding a distorted map.
- Hoel, Albantakis & Tononi (2013), *Quantifying causal emergence shows that macro can beat micro.* PNAS.
  The original claim that a macroscale can carry more causal information than the microscale.
- Rosas, Mediano, Jensen, Seth, Barrett, Carhart-Harris & Bor (2020), *Reconciling emergences: an information-theoretic approach to identify causal emergence in multivariate data.* PLOS Computational Biology 16, e1008289.
  A criterion for emergence that works on data, not only on known models.
- Gfeller & De Los Rios (2007), *Spectral coarse graining of complex networks.* Physical Review Letters 99, 038701.
  Coarse-graining that preserves the random-walk spectrum: the older baseline for dynamics-preserving reduction.

**Capstone.** Take one network, compute a causal-emergence measure along two renormalization flows, and show whether the best scale survives a change of scheme or of measure.

## Is branching one principle or many?

_Builds on: Renormalization and criticality._

Lungs, vessels, fungi, rivers and neural arbours all branch. Is there a shared principle, such as optimal transport, local growth rules or criticality, or only a family resemblance?

**What is unsettled.** Optimal-transport accounts predict scaling laws and loops, local growth rules produce branched forms without any optimisation, and adaptive feedback can retune a network after it grows. A branching process in time is also a different object from a branched network in space. Which measurement tells these accounts apart in a given system is open.

**The lab claim to test.** Stochastic branching, fusion and stopping, with no global optimisation or feedback, produce networks whose trade-offs between transport, exploration and robustness lie close to those of real fungal networks. Source: Lucas, Bisot, Petri, Declerck & Carletti (2026), *Minimal branching and fusion morphogenesis approaches biological multi-objective optimality.* arXiv:2601.03877

### Readings past the stream

- **Rival account.** Tero, Takagi, Saigusa, Ito, Bebber, Fricker, Yumiki, Kobayashi & Nakagaki (2010), *Rules for biologically inspired adaptive network design.* Science 327, 439–442.
  The strongest competing account: efficient networks from flow-driven feedback, not from growth rules alone.
- West, Brown & Enquist (1997), *A general model for the origin of allometric scaling laws in biology.* Science 276, 122–126.
  The optimal-transport account of biological scaling, and the predictions it makes.
- Katifori, Szöllősi & Magnasco (2010), *Damage and fluctuations induce loops in optimal transport networks.* Physical Review Letters 104, 048704.
  Why optimal networks sometimes have loops: damage and fluctuating load change the optimum.
- Hannezo, Scheele, Moad, Drogo, Heer, Sampogna, van Rheenen & Simons (2017), *A unifying theory of branching morphogenesis.* Cell 171, 242–255.
  Branching organs from local stochastic rules: the growth account in development.

**Capstone.** Take one branching system with data, fit an optimal-transport model and a local growth model, and name the measurement that separates them.

---

[Overview](README.md)
