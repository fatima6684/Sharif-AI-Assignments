# Probabilistic Inference and Particle Filtering

## Overview

This project implements fundamental concepts of probabilistic artificial intelligence, including Bayesian Networks, exact and approximate inference methods, and Particle Filters for state estimation.

The first part of the project focuses on building a Bayesian Network, defining conditional probability tables (CPTs), and performing probabilistic inference using both exact and sampling-based methods. The second part implements a Particle Filter to estimate the hidden state of a dynamic system using noisy observations and motion updates.

---

## Part 1: Bayesian Network Inference

A Bayesian Network is implemented to model dependencies between random variables using a directed acyclic graph (DAG) and Conditional Probability Tables (CPTs).

Implemented features:

- Defining Bayesian Network structures.
- Creating Conditional Probability Tables (CPTs).
- Performing exact inference using the Enumeration algorithm.
- Performing approximate inference using Likelihood Weighting.
- Comparing exact and approximate probability estimates.
- Visualizing inference results.

---

## Part 2: Particle Filtering

The project implements a Particle Filter for estimating the position of an agent in an uncertain environment.

Implemented steps:

### Initialization

- Creating a set of particles representing the initial belief distribution.

### Prediction (Motion Update)

- Updating particle positions based on the motion model.

### Correction (Measurement Update)

- Calculating particle weights according to sensor observations.
- Updating the belief distribution based on measurement likelihoods.

### Resampling

- Selecting new particles based on their calculated weights.
- Improving the approximation of the posterior distribution.

---

## Features

- Exact probabilistic inference.
- Sampling-based approximate inference.
- Likelihood weighting algorithm.
- Bayesian reasoning under uncertainty.
- Particle-based state estimation.
- Visualization of probability distributions and particle states.
- Comparison between different inference approaches.

---

## Technologies Used

- Python
- NumPy
- Matplotlib
- NetworkX
- Jupyter Notebook

---

## Learning Objectives

This project provides practical experience with:

- Modeling uncertainty using Bayesian Networks.
- Working with Conditional Probability Tables (CPTs).
- Understanding exact vs approximate inference.
- Applying Monte Carlo sampling techniques.
- Implementing Particle Filters for localization and state estimation.
- Visualizing probabilistic models and results.

---

## Course

Developed as part of the Artificial Intelligence course at Sharif University of Technology.
