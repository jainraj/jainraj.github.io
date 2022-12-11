---
layout: page
title: MoCo for Self-Supervised Learning
description: Course Work for E9 333 - Advanced Deep Representation Learning @ IISc (Aug - Dec 2022)
importance: 15
category: Academia
github: https://github.com/jainraj/ADRL-Course-Codes/tree/master/MoCo
---

In self-supervised learning, we hope to use unlabelled data to learn representations which are useful to perform 
some supervised tasks downstream. 

MoCo uses two transformations of a sample - one as key and another as query. Fixed number of keys are stored in the 
model. Two encoders are used - one for key and another for query. The model needs to predict which of the encoded keys, 
the encoded query is most similar to. The query encoder is trained and the key encoder is updated slowly from the query 
encoder. This was revolutionary in the sense that we don't need to large batch sizes (like SimCLR) or maintain a large 
dataset in a memory bank. 

All code and results are in my GitHub repo <a href="https://github.com/jainraj/ADRL-Course-Codes/tree/master/MoCo">
<i class="fab fa-github gh-icon"></i></a>.
