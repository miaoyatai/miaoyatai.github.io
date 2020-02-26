---
layout: archive
title: "Work"
permalink: /work/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

* Based on machine learning, the recognition of quantum state image and the regression analysis of magnetic field value are realized.
  * May. 2019 - Oct. 2019
  * Based on the Pytorch framework, I established an appropriate convolutional neural network for feature extraction and classification recognition of quantum state images. I optimized and adjusted the convolutional network structures of VGG16, VGG19 and 8-layers built by myself to find the network structure with the best recognition effect. On this basis, the magnetic field value regression analysis is carried out to predict the information represented by the new quantum state image.
 
 * Image classification is realized by depth residual network(ResNet)
   * Sep. 2019 - Oct. 2019
   * Based on the Pytorch framework, I built a deep residual network (ResNet), and conducted image classification experiments on Cifar10 and Cifar100 datasets respectively.Then continuously deepen the network to observe the model performance changes, find out resNet network deepening caused by the problem, and put forward the improvement plan.

 * Image annotation
   * May. 2019 - June. 2019
   * Training and testing in the Flickr dataset based on the Pytorch framework.Firstly, CNN(ResNet) was used to extract features and encode the input image.Then RNN(LSTM is used in this experiment) is used to decode the encoded image.Meanwhile, Attention mechanism was introduced into the experiment (Soft Attention was adopted in this experiment).After extracting the image features, the image features and the predicted word information are input to RNN to calculate the hidden layer output.The advantage of this is that it can be used to indicate which parts of the image to focus on based on the predicted word information, rather than aimlessly focusing on the whole image.
   
* MobileNet: A Lightweight Neural Network for Image Recognition
  * This is a lightweight network proposed by Google in 2017, and I tried to reproduce the network on my own for image recognition on CIFAR10 datasets with Pytorch, which only uses 10 layers of CNN without MaxPooling layer but achieved 92% accuracy.
  
* Implement Machine Learning Algorithms Without Framework
  * Implemented some machine learning algorithms with pure Python on my own, including K-Meansand AGNES Clustering, Bayesian Classification, Logistic Regression, ID3 Decision Tree and so on.

