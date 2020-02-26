---
layout: archive
title: "Work"
permalink: /work/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

* Image caption generation algorithm based on attention mechanism
  * Nov.2019-Present
  * I used CNN to extract the features of the image, and then extract the first feature point of theimage through the Attention mechanism (select the one with the highest correlation).
 
 * Apply attention mechanism to singing voice separation
   * Aug. 2019 - Oct. 2019
   * We  proposed  an  end-to-end  neural  network  based  on  self-attention  layer,  which  focuses  on  thesinging  voice  separation  task.   It  works  on  spectrogram  domain,  which  can  separate  songs  intoaccompaniments and vocals;
   * Compared with the baselines, the evaluation metric of our model is greatly improved while the
number of model parameters is significantly reduced.

* MobileNet: A Lightweight Neural Network for Image Recognition
  * This is a lightweight network proposed by Google in 2017, and I tried to reproduce the network on my own for image recognition on CIFAR10 datasets with Pytorch, which only uses 10 layers of CNN without MaxPooling layer but achieved 92% accuracy.
  
* Implement Machine Learning Algorithms Without Framework
  * Implemented some machine learning algorithms with pure Python on my own, including K-Meansand AGNES Clustering, Bayesian Classification, Logistic Regression, ID3 Decision Tree and so on.

