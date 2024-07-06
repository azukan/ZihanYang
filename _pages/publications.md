---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Parameter fitting approach for the piecewise quadratic neuron model using improved particle swarm optimization framework ##
Authors: <ins>Zihan Yang</ins> & Takashi Kohno

Published in _the 12th RIEC International Symposium on Brain Functions and Brain Computer_, Feb. 2024

**Abstract:**
Neurons are a basic unit of the nervous system. Understanding single neurons' dynamical properties and activity patterns is critical to understand the mysteries of the intelligent information processing in the brain. The Piecewise Quadratic Neuron (PQN) model is a spiking neuron model that can be efficiently implemented on digital arithmetic circuits. In addition, this model can precisely reproduce the activities of various neuronal classes. However,  an optimized parameter set has to be found to properly reproduce a target neuronal activity. The parameter space is very high-dimensional, thus many algorithms have been proposed including meta-heuristics. Two hybrid methods between the particle swarm and Bayesian optimization algorithms are proposed in this study. We fitted the two-variable PQN model to Class1 and Class2 neurons with these two methods and compared them with previous studies. The results show that our methods surpass them in the best, worst, and average results though longer computing time is required. Finally, we also performed parameter fitting to RS neurons in a three-variable PQN model. One of the two methods obtained stable results without modifying the framework and successfully fitted the spiking characteristics. The results show that our proposed algorithm can successfully fit the spiking characteristics of neurons and shows better results and reliability. In the future, we plan to validate the stability of our algorithm by applying it to more neuron classifications and parameter sets. We will also apply them for parameter fitting to real electrophysiology data. By refining architecture and parallel processing techniques, we expect to handle larger neuron models and datasets to reduce fitting times and increase the practicality for real-world applications. 


## LSTM-RNN based analog IC automated sizing model for operational amplifier and VCO ##

Authors: <ins>Zihan Yang</ins>, Wensi Wang, Zhijie Chen, Qianhui Fan & Xuanchong Chen

Published in _IEEE 5th International Conference on Integrated Circuits and Microsystems_, Oct. 2020

**Abstract:**

Artificial intelligence and machine learning have been widely used to replace human work. Analog integrated circuit design needs to adjust a large number of circuit parameters to satisfy the balance between various performance metrics, which now mostly rely on the experience of designers and sometimes of the intuitions. Machine learning has demonstrated the potential to aid the design of analog integrated circuits in the literature, whilst most of them adopted particle swarm intelligence and Bayesian optimization. However, the model training time and simulation run time are substantial when any circuit structure modification occurs. In this paper, Recurrent Neural Network (RNN) was used to automatically optimize the parameters sizing by giving requested performance. Training data sets for the RNN of component parameters and circuit performance were simulated using Cadence Spectre. After training for only 15 minutes, RNN learns to predict parameters by inputting gain, bandwidth, power and frequency, which can make critical circuit design decision significantly faster. The reliability and applicability of the algorithm was verified through the parameter prediction of integrated operational amplifier and VCO.

