---
date: 2024-08-25
description: " "
featured_image: "/images/Data_Images/Connelly_forest.png"
title: "Regression Forest Approaches to Gravity Wave Parameterization for Climate Projection
"
title2: " "
---
## Authors:
***David S. Connelly*** and ***Edwin P. Gerber***

[Read the full paper here](https://doi.org/10.1029/2023MS004184)
## Abstract:
We train random and boosted forests, two machine learning architectures based on regression trees, to emulate a physics-based parameterization of atmospheric gravity wave momentum transport. We compare the forests to a neural network benchmark, evaluating both offline errors and online performance when coupled to an atmospheric model under the present day climate and in 800 and 1,200 ppm CO2 global warming scenarios. Offline, the boosted forest exhibits similar skill to the neural network, while the random forest scores significantly lower. Both forest models couple stably to the atmospheric model, and control climate integrations with the boosted forest exhibit lower biases than those with the neural network.
<!--more-->
Integrations with all three data-driven emulators successfully capture the Quasi-Biennial Oscillation (QBO) and sudden stratospheric warmings, key modes of stratospheric variability, with the boosted forest more accurate than the random forest in replicating their statistics across our range of carbon dioxide perturbations. The boosted forest and neural network capture the sign of the QBO period response to increased CO2, though both struggle with the magnitude of this response under the more extreme 1,200 ppm scenario. To investigate the connection between performance in the control climate and the ability to generalize, we use techniques from interpretable machine learning to understand how the data-driven methods use physical information. We leverage this understanding to develop a retraining procedure that improves the coupled performance of the boosted forest in the control climate and under the 800 ppm CO2 scenario.

## Plain Language Summary:
Parameterizations are reduced-complexity models that estimate the effects of physical processes smaller than what can be resolved by the grid of a weather or climate model. While necessary for realistic simulations, they are a source of uncertainty in climate projections. Recently, machine learning has been used to augment or replace conventional parameterizations of atmospheric gravity waves, a type of motion by which disturbances near the Earth's surface can affect the wind higher up. We compare several machine learning approaches to the gravity wave parameterization problem. In particular, we test neural networks against random and boosted forests, which are built around flowchart-like models called regression trees. We find that boosted forests, though not widely used for climate model parameterization, are especially successful, scoring as well as or better than neural networks on various performance metrics. We then provide proof-of-concept of a novel method to retrain the boosted forest so that it uses its input data more in line with the physics of the system, and show that this technique improves the forest's behavior when used together with an atmospheric model.

## Key Points:
1. Two kinds of regression forest emulate a gravity wave parameterization offline and online, with boosted forests outperforming random forests
2. Relative to a neural network benchmark, the boosted forest exhibits similar online skill and ability to generalize to new climates
3. Feature importance analysis informs a retraining procedure to improve online behavior of data-driven parameterizations
