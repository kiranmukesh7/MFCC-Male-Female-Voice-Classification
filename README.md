# MFCC-Male-Female-Voice-Classification
MFCC based classification of Male-Female Voice

A Modified version of Tanh activation function is used (by custom definition), with the amplitude and origin of the Tanh function being variable (hyper-parameters).

A set of 4 classifiers have been tried. The performance of the kNN, Sigmoid Neuron and FFNN are comparable in terms of accuracy, with the FFNN accuracy better on average. 

A general configuration of neural network is tried and tested by k-fold (here, 5-fold) cross validation. 

The number of MFCC is variable and can be set by the user.
