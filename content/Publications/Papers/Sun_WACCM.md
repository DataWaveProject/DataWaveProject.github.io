---
date: 2024-07-26
description: " "
featured_image: "/images/Data_Images/Qiang_waccm.png"
title: "Data Imbalance, Uncertainty Quantification, and Transfer Learning in Data-Driven Parameterizations: Lessons From the Emulation of Gravity Wave Momentum Transport in WACCM"
title2: " "
---
## Authors:
***Qiang Sun***, ***Hamid Pahlavan***, ***Ashesh Chattopadhyay***,***Pedram Hassanzadeh***, Sandro Lubis, ***M. Joan Alexander***, ***Edwin Gerber***, ***Aditi Sheshadri***, and Yifei Guan

[Read the full paper here](https://doi.org/10.1029/2023MS004145)
## Abstract:
Neural networks (NNs) are increasingly used for data-driven subgrid-scale parameterizations in weather and climate models. While NNs are powerful tools for learning complex non-linear relationships from data, there are several challenges in using them for parameterizations. Three of these challenges are (a) data imbalance related to learning rare, often large-amplitude, samples; (b) uncertainty quantification (UQ) of the predictions to provide an accuracy indicator; and (c) generalization to other climates, for example, those with different radiative forcings. Here, we examine the performance of methods for addressing these challenges using NN-based emulators of the Whole Atmosphere Community Climate Model (WACCM) physics-based gravity wave (GW) parameterizations as a test case.
<!--more-->
WACCM has complex, state-of-the-art parameterizations for orography-, convection-, and front-driven GWs. Convection- and orography-driven GWs have significant data imbalance due to the absence of convection or orography in most grid points. We address data imbalance using resampling and/or weighted loss functions, enabling the successful emulation of parameterizations for all three sources. We demonstrate that three UQ methods (Bayesian NNs, variational auto-encoders, and dropouts) provide ensemble spreads that correspond to accuracy during testing, offering criteria for identifying when an NN gives inaccurate predictions. Finally, we show that the accuracy of these NNs decreases for a warmer climate (4 × CO2). However, their performance is significantly improved by applying transfer learning, for example, re-training only one layer using ∼1% new data from the warmer climate. The findings of this study offer insights for developing reliable and generalizable data-driven parameterizations for various processes, including (but not limited to) GWs.

## Plain Language Summary:
Scientists increasingly use machine learning methods, especially neural networks (NNs), to improve weather and climate models. However, it can be challenging for an NN to learn rare, large-amplitude events because they are infrequent in training data. In addition, NNs need to express their confidence (certainty) about a prediction and work effectively across different climates, for example, warmer climates due to increased CO2. Traditional NNs often struggle with these challenges. Here, we share insights from emulating known physics (gravity waves) with NNs in a state-of-the-art climate model. We propose specific strategies for effectively learning rare events, quantifying the uncertainty of NN predictions, and making reliable predictions across various climates. For instance, one strategy to address the learning of rare events involves inflating the impact of infrequent events in the training data. We also demonstrate that several methods could be useful in determining the uncertainty of the predictions. Furthermore, we show that NNs trained on simulations of the historical period do not perform as well in warmer climates. We then improve NN performance by employing transfer learning using limited new data from warmer climates. This study provides lessons for developing robust and generalizable approaches for using NNs to improve models in the future.

## Key Points:
1. Whole Atmosphere Community Climate Model's orographic, convective, and frontal gravity wave parameterizations are emulated using neural nets to inform future modeling efforts
2. Data imbalance is addressed via resampling and weighted loss; uncertainty quantification via Bayesian, dropout, and variational methods
3. Performance of the neural nets in a warmer climate is improved via transfer learning with ∼1% new data