---
title: "Temporal recurrence as a general mechanism to explain neural responses in the auditory system"
collection: publications
category: manuscripts
permalink: /publication/2024-statenet-biorxiv
excerpt: 'Using and reverse-engineering deep gated RNNs as auditory neural response models'
date: 2025-01-09
venue: 'bioRxiv'
#slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://www.biorxiv.org/content/10.1101/2025.01.08.631909v2'
citation: 'Rançon et al. (2025). &quot;Temporal recurrence as a general mechanism to explain neural responses in the auditory system.&quot; <i>BioRxiv</i>; doi: https://doi.org/10.1101/2025.01.08.631909'
---


Computational models of neural processing in the auditory cortex usually ignore that neurons have an internal memory: they characterize their responses from simple convolutions with a finite temporal window of arbitrary duration. To circumvent this limitation, we propose here a new, simple and fully recurrent neural network (RNN) architecture incorporating cutting-edge computational blocks from the deep learning community and constituting the first attempt to model auditory responses with deep RNNs. We evaluated the ability of this approach to fit neural responses from 8 publicly available datasets, spanning 3 animal species and 6 auditory brain areas, representing the largest compilation of this kind. Our recurrent models significantly out-perform previous methods and a new Transformer-based architecture of our design on this task, suggesting that temporal recurrence is the key to explain auditory responses. Finally, we developed a novel interpretation technique to reverse-engineer any pretrained model, regardless of their stateful or stateless nature. Largely inspired by works from explainable artificial intelligence (xAI), our method suggests that auditory neurons have much longer memory (several seconds) than indicated by current STRF techniques. Together, these results highly motivate the use of deep RNNs within computational models of sensory neurons, as protean building blocks capable of assuming any function.

