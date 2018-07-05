# Explainable - Artificial Intelligence

<p align="center">
  <img src="https://github.com/HSBC-RISE18/Explainable-AI/blob/master/data/HSBC%20logo.jpg" width="1000"/>
</p>

## LIME - Framework for Explaining AI

### Overview

<p align="center">
  <img src="https://github.com/HSBC-RISE18/Explainable-AI/blob/master/data/LIME%20Algorithm.png" width="500"/>
</p>

LIME calculates the similarity score via distance metric between permutations and the original observations. Thereafter, it runs the permutations through the predictor to identify the best describing features. The best describing features and the similarity score are used to compute a simpler model e.g. a linear regression. The calculated feature weights of the simpler model provides an explanation of the local behaviour of  the complex model.

### LIME - Python Package

https://github.com/marcotcr/lime is running a project which is about explaining what machine learning classifiers (or models) are doing.

At the moment, it supports explaining individual predictions for text classifiers or classifiers that act on tables (numpy arrays of numerical or categorical data) or images, with a package called lime (short for local interpretable model-agnostic explanations).

<a href="https://www.youtube.com/watch?v=hUnRCxnydCc" target="_blank"><img src="https://raw.githubusercontent.com/marcotcr/lime/master/doc/images/video_screenshot.png" width="450" alt="KDD promo video"/></a>

## Use Case - Credit Card Payment Default

In this use case LIME technique is applied on classifiers that are attempting to identify individual customers that have a high probability of defaulting on their next credit card payment.

### Comparison of Classifiers

<p align="center">
  <img src="https://github.com/HSBC-RISE18/Explainable-AI/blob/master/data/Comparison%20of%20Classifiers.png" width="500"/>
</p>

### Comparison of Clients

<p align="center">
  <img src="https://github.com/HSBC-RISE18/Explainable-AI/blob/master/data/Comparison%20of%20Clients.png" width="500"/>
</p>
