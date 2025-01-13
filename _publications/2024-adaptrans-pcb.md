---
title: "A general model unifying the adaptive, transient and sustained properties of ON and OFF auditory neural responses"
collection: publications
category: manuscripts
permalink: /publication/2024-adaptrans-pcb
excerpt: 'Augmenting and benchmarking models of auditory neural responses on various datasets'
date: 2024-08-02
venue: 'PLoS Computational Biology'
#slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1012288'
citation: 'Rançon et al. (2024). &quot;A general model unifying the adaptive, transient and sustained properties of ON and OFF auditory neural responses.&quot; <i>PLoS Computational Biology</i>; doi: https://doi.org/10.1371/journal.pcbi.1012288'
---


Sounds are temporal stimuli decomposed into numerous elementary components by the auditory nervous system. For instance, a temporal to spectro-temporal transformation modelling the frequency decomposition performed by the cochlea is a widely adopted first processing step in today’s computational models of auditory neural responses. Similarly, increments and decrements in sound intensity (i.e., of the raw waveform itself or of its spectral bands) constitute critical features of the neural code, with high behavioural significance. However, despite the growing attention of the scientific community on auditory OFF responses, their relationship with transient ON, sustained responses and adaptation remains unclear. In this context, we propose a new general model, based on a pair of linear filters, named AdapTrans, that captures both sustained and transient ON and OFF responses into a unifying and easy to expand framework. We demonstrate that filtering audio cochleagrams with AdapTrans permits to accurately render known properties of neural responses measured in different mammal species such as the dependence of OFF responses on the stimulus fall time and on the preceding sound duration. Furthermore, by integrating our framework into gold standard and state-of-the-art machine learning models that predict neural responses from audio stimuli, following a supervised training on a large compilation of electrophysiology datasets (ready-to-deploy PyTorch models and pre-processed datasets shared publicly), we show that AdapTrans systematically improves the prediction accuracy of estimated responses within different cortical areas of the rat and ferret auditory brain. Together, these results motivate the use of our framework for computational and systems neuroscientists willing to increase the plausibility and performances of their models of audition.

