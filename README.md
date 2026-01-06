# Physics_inspired_machinelearning
Creating projects where maths, physics, and ML intersect to form a beautiful cacophony
# Physics-ML Theory Implementation Notebooks

## Overview
10 self-contained notebooks testing physics-inspired machine learning theories with executable code, visualizations, and benchmarks.

### 01_heavy_tailed_sgd_analyzer
Tracks gradient statistics during training to detect Lévy α-stable distributions and correlate tail exponents with generalization gaps during phase transitions.

### 02_mps_attention
Replaces standard attention with Matrix Product State decomposition, where bond dimension χ controls information flow capacity and correlation length.

### 03_adjoint_control
Implements GRAPE-style pulse optimization using adjoint method with control constraints to test if bounded updates improve adversarial robustness.

### 04_fisher_preconditioning
Natural gradient descent via empirical Fisher information matrix, tracking condition number evolution at grokking transitions and double descent.

### 05_nonmarkovian_memory
Attention with learnable power-law memory kernel K(τ)~τ^(-μ) where μ per head specializes to different timescales for long-range dependencies.

### 06_rg_pruning
Renormalization group pruning that integrates out irrelevant neurons via effective couplings while preserving loss landscape critical structure.

### 07_path_integral_training
Samples ensemble of training trajectories via Metropolis-Hastings on action S[θ(t)]=∫[kinetic+loss]dt to find flatter minima than single-path SGD.

### 08_conformal_symmetry
Measures layer correlation power laws C(l,l')~|l-l'|^(-2Δ) to extract scaling dimensions and test if training preserves conformal invariance.

### 09_schwinger_dyson_attention
Self-consistent attention via fixed-point iteration G=G₀+G₀ΣG using Dyson resummation to capture infinite-order interactions for transitive reasoning.

### 10_lattice_qft_optimization.
Hybrid Monte Carlo on discrete weight lattice {-1,0,+1} with topological charge tracking to test sector-dependent generalization.

### 11_kitaev_chain_vqe
Variational Quantum Eigensolver implementation for Kitaev chain to detect topological phase transitions via spectral gap and string order parameter.
