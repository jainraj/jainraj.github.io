---
layout: page
title: Contrastive Divergence for Energy Based Models
description: Course Work for E9 333 - Advanced Deep Representation Learning @ IISc (Aug - Dec 2022)
importance: 17
category: Academia
github: https://github.com/jainraj/ADRL-Course-Codes/tree/master/EBM
---

Energy based Models (EBMs) have a much simpler philosophy. One assumes the data distribution to follow the form 

$$ p_{\theta}(x) = \frac{exp(-E_{\theta}(x))}{z_{\theta}} $$

$$E_{\theta}(x)$$ is what is modelled as a neural network. To generate samples from the model, one uses Langevin 
dynamics, as it does not rely on estimation of $$z_{\theta}$$, which can be expensive. 

To train the model, one can use multiple methods. One computationally tractable method is to use Contrastive 
Divergence, introduced by Hinton. Here, I implement contrastive divergence for modelling and generating Bitmoji
images.

All code and results are in my GitHub repo <a href="https://github.com/jainraj/ADRL-Course-Codes/tree/master/EBM">
<i class="fab fa-github gh-icon"></i></a>.
