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
