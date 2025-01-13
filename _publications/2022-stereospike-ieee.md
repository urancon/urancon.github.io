---
title: "StereoSpike: Depth Learning With a Spiking Neural Network"
collection: publications
category: manuscripts
permalink: /publication/2022-stereospike-ieee
excerpt: 'Stereo depth estimation from event cameras with a SNN'
date: 2022-12-02
venue: 'IEEE Access'
#slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://ieeexplore.ieee.org/document/9969606'
citation: 'Rançon et al. (2022). &quot;StereoSpike: Depth Learning with a Spiking Neural Network.&quot; <i>IEEE Access</i>; doi: 10.1109/ACCESS.2022.3226484'
---


Depth estimation is an important computer vision task, useful in particular for navigation in autonomous vehicles, or for object manipulation in robotics. Here, we propose to solve it using StereoSpike, an end-to-end neuromorphic approach, combining two event-based cameras and a Spiking Neural Network (SNN) with a modified U-Net-like encoder-decoder architecture. More specifically, we used the Multi Vehicle Stereo Event Camera Dataset (MVSEC). It provides a depth ground-truth, which was used to train StereoSpike in a supervised manner, using surrogate gradient descent. We propose a novel readout paradigm to obtain a dense analog prediction–the depth of each pixel– from the spikes of the decoder. We demonstrate that this architecture generalizes very well, even better than its non-spiking counterparts, leading to near state-of-the-art test accuracy. To the best of our knowledge, it is the first time that such a large-scale regression problem is solved by a fully spiking neural network. Finally, we show that very low firing rates (< 5%) can be obtained via regularization, with a minimal cost in accuracy. This means that StereoSpike could be efficiently implemented on neuromorphic chips, opening the door for low power and real time embedded systems.
