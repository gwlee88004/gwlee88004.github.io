---
layout: default
title: Research Overview
---

<!-- <h1>Selected Research Topics</h1>
<p>Below are highlights of my research work, focusing on innovative methods for monitoring critical infrastructure and analyzing wave-based data. Each section provides a brief introduction, with links to detailed explanations for further exploration.</p> -->

## **Condition Monitoring for Spent Nuclear Fuel Storage**
Condition monitoring for spent nuclear fuel storage requires reliable methods to assess the structural health of hollow cylinders made of welded plates, with sensors deployed by robots. Reducing the number of sensing points is essential to streamline the process and maintain efficiency.


## 3D Defect Localization Using Defect-Induced Waves
### *Deep Learning, Bayesian Framework, Pattern Recognition, Segmentation, Time-series Data* <a target="_blank" href="https://doi.org/10.1177/14759217241260254">[Journal Article]</a>

<img src="{{ "/assets/img/content/vae/aiken_site.jpg" | absolute_url }}" alt="helical paths figure" style="float: right; margin: 20px 20px 20px 20px; ;max-width: 200px" />
* **Task**: Locate defects by analyzing naturally occurring disturbances within a system, rather than actively introducing external inputs, for real-time monitoring. 
* **Method**: Utilized a Variational Autoencoder (VAE) to identify physics-based propagation patterns of defect-induced waveforms and modeled localization variables using Bayesian frameworks.
* **Novelty**: Achieved 93% accuracy defect localization using only two sensors, demonstrated the ability to identify and localize defects with minimal data, improving practicality and efficiency for real-world applications.
<a href="/pages/ae3dloc/">More Details</a>

## Generative model for Wavefield Simulation
### *Physic-Based ML, WaveNet Generative AI, Surrogate model*
<img src="{{ "/assets/img/content/generated_spectrogram.gif" | absolute_url }}" alt="helical paths figure" style="float: right; margin: 20px 20px 20px 20px; ;max-width: 200px" />
* **Task**: Assess structural health by applying controlled signals and analyzing the structure's response.
* **Method**: Designed a WaveNet-based generative model to surrogate wavefields using sparse sensor readings. 
* **Novelty**: Enabled baseline-free monitoring and practical high-resolution wavefield data collection on curved surfaces where traditional scanning is not feasible.
