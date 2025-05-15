# asi-assignment
This repository contains an advanced implementation of Bayesian Neural Networks using the Bayes by Backprop algorithm created by Krisostomus Nova RAHMANTO. This project was developed as part of the Advanced Statistical Inference (ASI) course at EURECOM (Spring 2025).

## Overview
- Implementation of weight uncertainty through variational inference.
- A PyTorch-based Bayesian neural network with custom BayesianLinear layers.
- Training on the FashionMNIST dataset with detailed uncertainty analysis.
- Evaluation using both in-domain (FashionMNIST) and out-of-domain (MNIST) data.
- Visualization of model uncertainty using Monte Carlo sampling and TensorBoard logging.

## Contents
- **Modeling:** Bayesian network architecture with three fully connected layers.
- **Training:** Custom training loop with ELBO loss computation and probabilistic sampling.
- **Evaluation:** Ensemble predictions, accuracy logging, and uncertainty visualization.
- **Experiments:** Detailed analysis of epistemic uncertainty for in-distribution and novel inputs.
