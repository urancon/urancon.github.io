---
title: "DeepSTRF: a PyTorch library for sensory neural response modeling with deep neural networks"
#excerpt: "Github repository (PyTorch) <br/><img src='/images/500x300.png'>"
collection: portfolio
---

Repository URL: [https://github.com/urancon/deepSTRF](https://github.com/urancon/deepSTRF)

Motivations
================
During my PhD, I have been using deep neural networks to quantitatively model single unit responses in sensory (auditory/visual) cortex of mammals.
Doing so, I have found myself lost with a variety of data formats and preprocessing methods, which make it difficult to fairly compare computational models of neural responses.
In general, electrophysiologists and computational neuroscientists test their own model on their own data, and rarely attempt to compare the performances of their model with others. As a result, there is no such thing as a "state-of-the-art" for this machine learning task in this community.
Coming from a deep learning background where benchmarking plays a crucial role, I wanted to change this and make it easier for AI engineers to come tackle this problem of neural response fitting.
As a result, I proposed the deepSTRF python library.


DeepSTRF
================
It currently comprises instructions for preprocessing several datasets in the form of a standard torch Dataset class.
Additionally, it comes with a model zoo and methods to train models on a GPU, in population coding (the model tries to predict the activity of a population of neurons at the same time).

If you're interested by this task, please give it a try! If you would like to help me make it grow as a library, by integrating more datasets and models, don't hesitate to contact me !




