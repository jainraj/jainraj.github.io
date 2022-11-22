---
layout: page
title: Cycle Wasserstein GANs
description: Course Work for E9 333 - Advanced Deep Representation Learning @ IISc (Aug - Dec 2022)
importance: 18
category: Academia
github: https://github.com/jainraj/ADRL-Course-Codes/tree/master/CycleWGAN
---

Generative Adversarial Network (GAN) is a generative model to map any simple distribution to a distribution of interest 
by using two neural networks. One maps a latent to datapoint and another is trained such that it is unable to determine
whether the input is from the actual data samples or converted from latent. Usual GANs have issues in training. 
Wasserstein GANs attempt to solve this problem by training a critic network which gives an unbounded score as output.

CycleGANs are a special type of GANs introduced for unlabelled image-to-image translations. One such usecase is to convert 
a painting to a photograph and vice-versa. The basic idea of GAN is to learn function to transform simple distributions 
to data distributions, CycleGAN takes this idea further to learn functions to transform between two data distributions. 

Here, I implement a CycleGAN which uses Wasserstein metric as loss. All code and results are in my GitHub repo 
<a href="https://github.com/jainraj/ADRL-Course-Codes/tree/master/CycleWGAN">
<i class="fab fa-github gh-icon"></i></a>.
