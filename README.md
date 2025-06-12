# asi-assignment
This repository presents a reproducible implementation of Bayesian Neural Networks using the Bayes by Backprop algorithm, as developed by Krisostomus Nova RAHMANTO. This work was undertaken as part of the Advanced Statistical Inference (ASI) course at EURECOM (Spring 2025).

## Overview
- Implementation of weight uncertainty via variational inference.
- A PyTorch-based Bayesian neural network employing two BayesianLinear layers.
- Training and evaluation conducted on the MNIST dataset with rigorous uncertainty quantification.
- Comparison against baseline models including DropoutNN and VanillaNN.
- Detailed hyperparameter tuning, Monte Carlo sampling for ELBO estimation, and extensive analysis of weight distributions and model uncertainty.

## Contents
- **Modeling:** Bayesian network architecture with configurable hidden units and two stochastic layers.
- **Training:** A custom training loop that incorporates KL divergence reweighting, learning rate decay, and Monte Carlo approximation of the ELBO loss.
- **Evaluation:** Ensemble predictions with uncertainty estimation, comparative analysis among Bayesian and deterministic approaches, and visualization of posterior distributions.
- **Experiments:** Systematic hyperparameter tuning and comprehensive diagnostic plots that illustrate convergence behavior and the impact of model regularization.
