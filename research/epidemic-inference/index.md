---
layout: single
permalink: /research/epidemic-inference/
author_profile: false
sidebar:
  nav: false
---

<!-- Banner d'intestazione a tutta larghezza (Inerenza Epidemica) -->
<div style="
  position: relative;
  width: 100vw;
  left: 50%;
  right: 50%;
  margin-left: -50vw;
  margin-right: -50vw;
  height: 220px;
  background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('{{ site.baseurl }}/assets/images/banner-epidemic-inference.png') center/cover no-repeat;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-top: -2rem;
  margin-bottom: 2.5rem;
">
  <h1 style="
    color: #ffffff;
    font-size: 2.2rem;
    font-weight: 700;
    text-align: center;
    margin: 0;
    padding: 0 20px;
    text-shadow: 0 2px 6px rgba(0, 0, 0, 0.7);
  ">
    Epidemic Inference & Control
  </h1>
</div>

Epidemic spreading on contact networks provides a particularly rich setting in which to study inference, prediction, and control in complex dynamical systems.

My research in this area combines **statistical physics, probabilistic inference, and network dynamics** to address questions such as: What is the current state of an epidemic when observations are incomplete? Where did an outbreak originate? How can contact-tracing information be used to reconstruct transmission paths? And how can interventions be optimized under limited information?

<br>

## Epidemic State Inference

A central problem is the reconstruction of the hidden state of an epidemic from incomplete observations. The combination of network structure and stochastic transmission dynamics makes this a naturally distributed inference problem.

Message-passing and Bayesian approaches allow information from observed individuals to be propagated through the contact network while accounting explicitly for uncertainty.

### Selected publications

- A. Braunstein, G. Catania, L. Dall’Asta, M. Mariani, F. Mazza & M. Tarabolo, **Small-coupling dynamic cavity: A Bayesian mean-field framework for epidemic inference**, *Physical Review Research* (2025).
- I. Biazzo, A. Braunstein, L. Dall’Asta & F. Mazza, **A Bayesian generative neural network framework for epidemic inference problems**, *Scientific Reports* (2022).
- J. Bindi, A. Braunstein & L. Dall’Asta, **Predicting epidemic evolution on contact networks from partial observations**, *PLOS ONE* (2017).

<br>

## Contact Tracing & Transmission Reconstruction

Contact tracing provides partial information about the transmission history of an epidemic. An important challenge is to combine this information with a statistical model of spreading in order to reconstruct likely transmission paths and identify individuals or contacts that are particularly informative.

My work investigates the effectiveness of probabilistic contact tracing and the role of network heterogeneity, including the impact of superspreaders.

### Selected publications

- A. P. Muntoni, F. Mazza, A. Braunstein, G. Catania & L. Dall’Asta, **Effectiveness of probabilistic contact tracing in epidemic containment: The role of superspreaders and transmission path reconstruction**, *PNAS Nexus* (2024).
- A. Baker et al., **Epidemic mitigation by statistical inference from contact tracing data**, *Proceedings of the National Academy of Sciences* (2021).

<br>

## Epidemic Source Detection & Reconstruction

Identifying the origin of an outbreak is an inverse problem on a dynamical network. The available observations are typically noisy and incomplete, while the underlying transmission process is stochastic.

Statistical-mechanical inference provides a framework for estimating hidden sources and reconstructing epidemic histories from partial observations.

### Selected publications

- J. Bindi, A. Braunstein & L. Dall’Asta, **Predicting epidemic evolution on contact networks from partial observations**, *PLOS ONE* (2017).
- A. P. Muntoni et al., **Effectiveness of probabilistic contact tracing in epidemic containment: The role of superspreaders and transmission path reconstruction**, *PNAS Nexus* (2024).

<br>

## Intervention & Epidemic Control

Inference is ultimately useful when it can inform intervention. A major direction of this research is therefore the design of strategies for containment and mitigation under incomplete information.

This connects epidemic inference with optimization and statistical physics: interventions must be targeted at the right individuals or contacts while accounting for uncertainty in the reconstructed epidemic state.

### Selected publications

- A. Baker et al., **Epidemic mitigation by statistical inference from contact tracing data**, *Proceedings of the National Academy of Sciences* (2021).
- F. Altarelli, A. Braunstein, L. Dall’Asta, J. R. Wakeling & R. Zecchina, **Containing Epidemic Outbreaks by Message-Passing Techniques**, *Physical Review X* (2014).
