---
layout: page
title: ADDA & Cycle WGAN for Unsupervised Domain Adaptation
description: Course Work for E9 333 - Advanced Deep Representation Learning @ IISc (Aug - Dec 2022)
importance: 16
category: Academia
github: https://github.com/jainraj/ADRL-Course-Codes/tree/master/DomainAdap
---

In Unsupervised Domain Adaptation (UDA), we have two domains called source and target. Source labels are known but not 
the target labels. The domains are assumed to be "similar" to each other. 

Adversarial Discriminative Domain Adaptation 
(ADDA) solves the UDA problem in three stages. First stage is training a feature extractor with a classification head. 
Then, a target feature extractor is learnt adversarially using Wasserstein metric. Third, the target feature extractor 
is used with the source classification head. 

Cycle WGAN is another approach for this problem in which we train a Cycle 
GAN to learn the mapping between two domains using Wasserstein metric. Preliminary experiments showed that using weight 
clipping didn't give good results. So we shifted to gradient penalty approach. 

All code and results are in my GitHub repo <a href="https://github.com/jainraj/ADRL-Course-Codes/tree/master/DomainAdap">
<i class="fab fa-github gh-icon"></i></a>.
