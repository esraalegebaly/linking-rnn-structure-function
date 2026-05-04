# linking-rnn-structure-function
Replication and extension of Feulner et al. 2020 — exploring how RNN connectivity structure shapes neural manifolds and motor learning dynamics
Replication of Feulner et al. 2020

## Questions
- Q1: Training dynamics & loss curve
- Q2: Connection density vs performance
- Q3: Connectivity sparsity
- Q4: Network graph properties
- Q5: Task complexity & manifolds
- Q6: Decoder-only learning
- Q7-9: Advanced extensions
Linking RNN Structure to Function: Neural Manifold Realignment

Project Overview
This project investigates how **Recurrent Neural Networks (RNNs)** develop internal representations to solve complex motor tasks. By characterizing the **population geometry** of neural manifolds, we aim to understand the co-evolution of neural structure and functional output. This work is a foundational step toward the **NeuroRecovery** framework, designed to optimize Brain-Computer Interfaces (BCIs) for clinical motor rehabilitation.
Key Research Aims
* **Manifold Characterization**: Systematically quantifying the intrinsic dimensionality and curvature of neural representations during learning.
* **Task Complexity**: Analyzing how increasing the number of motor targets influences the linear separability of neural states.
* **Decoder Plasticity**: Comparing fixed vs. adaptive feedforward decoders to evaluate recovery efficiency in post-injury simulations.

Technical Implementation
* **Model**: Recurrent Neural Networks (RNNs) trained on multi-target reaching tasks.
* **Dimensionality Reduction**: Utilizing **Isomap**, **PCA**, and **UMAP** to visualize manifold structure.
* **Representational Analysis**: Implementing **Representational Dissimilarity Matrices (RDMs)** to quantify state-space organization.

Visualizations
The repository includes scripts to generate:
1. **Target-Specific Manifolds**: 3D Isomap projections showing neural separability.
2. **Learning Dynamics**: MSE curves comparing plastic vs. fixed decoder architectures.
3. **Curvature Evolution**: Tracking the "smoothing" of manifolds over training epochs.

Clinical Application: NeuroRecovery
Grounding motor rehabilitation in neural manifold geometry allows for the development of adaptive neuroprosthetics that "realign" with the user's changing neural signatures post-stroke or injury.
