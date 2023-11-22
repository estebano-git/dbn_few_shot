# Overview and implementation of a Deep Belief Network (DBN)
## Introduction
The biological inspiration of Articial Neural Networks as well as a brief theoretical background of DBNs is given.
A DBN can be seen as the stacking of several Restricted Boltzmann Machines, having the advantage of RBMs which learn a representation of the data through unsupervised learning. A linear classifier can be coupled to the last layer to have a linear readout for e.g. classification.
## Implementation
A DBN is trained using the FashionMNIST dataset
## Visual processing
Learned weights through the layers are visualized to observe what the model has learned. 
## Linear read outs
A linear model is added to have a linear read out for classification
## Comparison with a Feed Forward Neural Network
We compare our DBN with a FFN for benchmarking.
## Internal representation of the model
We use observe how the model clustered together similarities in the data at each hidden layer.
## Robustness to noise
Observe the impact that noise has on the DBN accuracy.
## Adversial attacks
We explore how the DBN classifies when faced against adversarial attacks, when using both reconstruction of the original image and when not.
## Few shot learning
Finally the DBN was fine-tuned with a linear classifier that is trained on only a small number of samples, achieving a high accuracy due to the internal representation being already learned while training.

