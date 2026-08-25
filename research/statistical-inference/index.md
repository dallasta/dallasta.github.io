---
layout: single
title: "Statistical Inference in Complex Networks"
permalink: /research/statistical-inference/
author_profile: false
sidebar:
  nav: false
---

Statistical inference in high-dimensional interacting systems is a central theme of my research. I develop analytical and computational methods inspired by statistical mechanics to reconstruct hidden variables, infer interactions, and characterize dynamical processes from partial and noisy observations.

A recurring objective is to develop **distributed inference methods** that remain tractable in systems with many interacting degrees of freedom, where conventional inference approaches become computationally prohibitive.

<br>

## Cavity Methods & Message Passing

Message-passing and cavity methods provide a natural framework for studying probabilistic models on sparse and heterogeneous networks. My work explores how these methods can be extended beyond static equilibrium systems to describe dynamical processes and stochastic interacting systems.

Recent work focuses in particular on **dynamic cavity methods**, including controlled approximations for systems with weak interactions and their interpretation as Bayesian mean-field approaches.

### Selected publications

- A. Braunstein, G. Catania, L. Dall’Asta, M. Mariani, F. Mazza & M. Tarabolo, **Small-coupling dynamic cavity: A Bayesian mean-field framework for epidemic inference**, *Physical Review Research* (2025).
- M. Tarabolo & L. Dall’Asta, **Gaussian approximation of dynamic cavity equations for linearly-coupled stochastic dynamics**, *SciPost Physics* (2025).
- A. Braunstein, G. Catania & L. Dall’Asta, **Loop Corrections in Spin Models through Density Consistency**, *Physical Review Letters* (2019).

<br>

## Inference in Dynamical Systems

A major challenge in networked systems is to infer the underlying state and dynamics when observations are incomplete. I study statistical-mechanical approaches to this problem, with an emphasis on the relationship between dynamics, causality, and probabilistic inference.

This includes methods for reconstructing hidden dynamical variables and for performing inference when the observed trajectories have been conditioned by the dynamics itself.

### Selected publications

- A. Braunstein, G. Catania, L. Dall’Asta, M. Mariani & A. P. Muntoni, **Inference in conditioned dynamics through causality restoration**, *Scientific Reports* (2023).
- A. Braunstein, G. Catania, L. Dall’Asta & A. P. Muntoni, **A density consistency approach to the inverse Ising problem**, *Journal of Statistical Mechanics: Theory and Experiment* (2021).
- A. Braunstein, G. Catania & L. Dall’Asta, **Loop Corrections in Spin Models through Density Consistency**, *Physical Review Letters* (2019).

<br>

## Graphical Models & Inverse Problems

Statistical physics provides powerful tools for inference in graphical models, where the structure of the interaction network plays a fundamental role.

My work in this direction includes inverse problems in spin systems and the development of approximations that retain information about correlations beyond standard mean-field descriptions.

### Selected publications

- A. Braunstein, G. Catania, L. Dall’Asta & A. P. Muntoni, **A density consistency approach to the inverse Ising problem**, *Journal of Statistical Mechanics: Theory and Experiment* (2021).
- A. Braunstein, G. Catania & L. Dall’Asta, **Loop Corrections in Spin Models through Density Consistency**, *Physical Review Letters* (2019).

<br>

## Distributed Inference on Networks

Many inference problems of practical interest involve large systems in which information is distributed across a network. Message-passing algorithms provide a principled way of exploiting locality while retaining information about global collective behaviour.

This perspective connects the methodological development of inference algorithms with applications to epidemic spreading, network dynamics, and other interacting systems.

### Selected publications

- A. Braunstein et al., **Small-coupling dynamic cavity: A Bayesian mean-field framework for epidemic inference**, *Physical Review Research* (2025).
- A. Biazzo, A. Braunstein, L. Dall’Asta & F. Mazza, **A Bayesian generative neural network framework for epidemic inference problems**, *Scientific Reports* (2022).
- J. Bindi, A. Braunstein & L. Dall’Asta, **Predicting epidemic evolution on contact networks from partial observations**, *PLOS ONE* (2017).