---
date: 2024-07-17
description: " "
featured_image: "/images/Data_Images/Mansfield_pub1.png"
title: "Uncertainty Quantification of a Machine Learning Subgrid-Scale Parameterization for Atmospheric Gravity Waves"
title2: " "
---
## Authors:
***Laura Mansfield*** and ***Aditi Sheshadri***

[Read the full paper here](https://doi.org/10.1029/2024MS004292)
## Abstract:
Subgrid-scale processes, such as atmospheric gravity waves (GWs), play a pivotal role in shaping the Earth's climate but cannot be explicitly resolved in climate models due to limitations on resolution. Instead, subgrid-scale parameterizations are used to capture their effects. Recently, machine learning (ML) has emerged as a promising approach to learn parameterizations. In this study, we explore uncertainties associated with a ML parameterization for atmospheric GWs. 
<!--more-->
Focusing on the uncertainties in the training process (parametric uncertainty), we use an ensemble of neural networks to emulate an existing GW parameterization. We estimate both offline uncertainties in raw NN output and online uncertainties in climate model output, after the neural networks are coupled. We find that online parametric uncertainty contributes a significant source of uncertainty in climate model output that must be considered when introducing NN parameterizations. This uncertainty quantification provides valuable insights into the reliability and robustness of ML-based GW parameterizations, thus advancing our understanding of their potential applications in climate modeling.
## Plain Language Summary:
Climate models are unable to resolve processes that vary on length and time scales smaller than the model resolution and timestep. For example, atmospheric gravity waves (GWs), which are waves created when winds encounter disturbances to the flow, such as mountains, convection and fronts, can have wavelengths smaller than the spacing between grid cells. Climate models use “parameterizations” to capture the effect of these processes. Machine learning based parameterizations are becoming popular because they can learn relationships purely from data. However, we do not have a good understanding of the uncertainties introduced through machine learning parameterizations. This study estimates uncertainties associated with training a neural network (NN) GW parameterization. We explore uncertainties in the NN output, as well as the uncertainties in the climate model output, when the NN is used for the GW parameterization.

## Key Points:
1. Using ensembles of neural networks, we learn parametric uncertainties associated with an emulator of a gravity wave parameterization
2. When coupled to the climate model, the ensemble of neural networks reveals increased climate variability
3. Parametric uncertainty dominates the Quasi-Biennial Oscillation statistics, although polar vortex properties remain robust to parameters