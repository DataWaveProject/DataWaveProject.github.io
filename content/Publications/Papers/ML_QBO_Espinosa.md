---
date: 2022-04-11
description: " "
featured_image: "/images/Data_Images/Espinosa_pub.png"
title: "Machine Learning Gravity Wave Parameterization Generalizes to Capture the QBO and Response to Increased CO2"
title2: " "
---
## Authors:
***Zachary Espinosa***, ***Aditi Sheshadri***, Gerald Cain, ***Edwin Gerber***, and Kevin DallaSanta

[Read the full paper here](https://doi.org/10.1029/2022GL098174)
## Abstract:
We present single-column gravity wave parameterizations (GWPs) that use machine learning to emulate non-orographic gravity wave (GW) drag and demonstrate their ability to generalize out-of-sample.

<!--more-->
  
A set of artificial neural networks (ANNs) are trained to emulate the momentum forcing from a conventional GWP in an idealized climate model, given only one view of the annual cycle and one phase of the Quasi-Biennial Oscillation (QBO). We investigate the sensitivity of offline and online performance to the choice of input variables and complexity of the ANN. When coupled with the model, moderately complex ANNs accurately generate full cycles of the QBO. When the model is forced with enhanced CO2, its climate response with the ANN matches that generated with the physics-based GWP. That ANNs can accurately emulate an existing scheme and generalize to new regimes given limited data suggests the potential for developing GWPs from observational estimates of GW momentum transport.

## Plain Language Summary:
Atmospheric gravity waves (GWs) or “buoyancy waves” are generated by perturbations in a stably-stratified environment. They mediate momentum transport between the lower and middle atmospheres and play a leading-order role in driving middle atmospheric circulation. Due to computational constraints, global climate models “parameterize” or estimate the effect of GWs on the large-scale flow. Current climate predictions are sensitive to uncertainties in these representations. Here, we examine whether machine learning, given limited data, can be used for gravity wave parameterization (GWP) in climate prediction. This approach represents an appealing technique to build data-driven GWPs that can reduce existing uncertainties by incorporating observations.

## Key Points:
1. Neural networks trained on one annual cycle accurately emulate a physics-based gravity wave parameterization (GWP) when coupled to a climate model
2. Although trained on only one phase of the Quasi-Biennial Oscillation, the emulator generates the entire cycle of the oscillation
3. The emulator captures key qualitative features of the response of the original GWP to enhanced CO2
