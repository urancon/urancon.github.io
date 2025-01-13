---
title: "Optical flow estimation from event-based cameras and spiking neural networks"
collection: publications
category: manuscripts
permalink: /publication/2023-opticflow-frontiers
excerpt: 'Optic flow regression from even-based cameras with SNNs on MVSEC and DSEC datasets'
date: 2023-05-11
venue: 'Frontiers in Neuroscience'
#slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2023.1160034/full'
citation: 'Cuadrado et al. (2023). &quot;Optical flow estimation from event-based cameras and spiking neural networks.&quot; <i>Frontiers in Neuroscience</i>; doi:  https://doi.org/10.3389/fnins.2023.1160034'
---

Event-based cameras are raising interest within the computer vision community. These sensors operate with asynchronous pixels, emitting events, or “spikes”, when the luminance change at a given pixel since the last event surpasses a certain threshold. Thanks to their inherent qualities, such as their low power consumption, low latency, and high dynamic range, they seem particularly tailored to applications with challenging temporal constraints and safety requirements. Event-based sensors are an excellent fit for Spiking Neural Networks (SNNs), since the coupling of an asynchronous sensor with neuromorphic hardware can yield real-time systems with minimal power requirements. In this work, we seek to develop one such system, using both event sensor data from the DSEC dataset and spiking neural networks to estimate optical flow for driving scenarios. We propose a U-Net-like SNN which, after supervised training, is able to make dense optical flow estimations. To do so, we encourage both minimal norm for the error vector and minimal angle between ground-truth and predicted flow, training our model with back-propagation using a surrogate gradient. In addition, the use of 3d convolutions allows us to capture the dynamic nature of the data by increasing the temporal receptive fields. Upsampling after each decoding stage ensures that each decoder's output contributes to the final estimation. Thanks to separable convolutions, we have been able to develop a light model (when compared to competitors) that can nonetheless yield reasonably accurate optical flow estimates.

