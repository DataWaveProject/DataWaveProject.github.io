---
date: 2024-04-27
description: " "
featured_image: "/images/Data_Images/Has_Momentum.png"
title: "Reconstructing Balloon-Observed Gravity Wave Momentum Fluxes Using Machine Learning and Input From ERA5"
title2: " "
---
## Authors:
***Sothea Has***, ***Riwal Plougonven***, Aurélie Fischer, ***Raj Rani***, ***Francois Lott***, ***Albert Hertzog***, ***Aurélien Podglajen***, ***Milena Corcos***

[Read the full paper here](https://doi.org/10.1029/2023JD040281)
## Abstract:
Global atmospheric models rely on parameterizations to capture the effects of gravity waves (GWs) on middle atmosphere circulation. As they propagate upwards from the troposphere, the momentum fluxes associated with these waves represent a crucial yet insufficiently constrained component. The present study employs three tree-based ensemble machine learning (ML) techniques to probe the relationship between large-scale flow and small-scale GWs within the tropical lower stratosphere.
<!--more-->
The measurements collected by eight superpressure balloons from the Strateole 2 campaign, comprising a cumulative observation period of 680 days, provide valuable estimates of the gravity wave momentum fluxes (GWMFs). Multiple explanatory variables, including total precipitation, wind, and temperature, were interpolated from the ERA5 reanalysis at each balloon's location. The ML methods are trained on data from seven balloons and subsequently utilized to estimate reference GWMFs of the remaining balloon. We observed that parts of the GW signal are successfully reconstructed, with correlations typically around 0.54 and exceeding 0.70 for certain balloons. The models show significantly different performances from one balloon to another, whereas they show rather comparable performances for any given balloon. In other words, limitations from training data are a stronger constraint than the choice of the ML method. The most informative inputs generally include precipitation and winds near the balloons' level. However, different models highlight different informative variables, making physical interpretation uncertain. This study also discusses potential limitations, including the intermittent nature of GWMFs and data scarcity, providing insights into the challenges and opportunities for advancing our understanding of these atmospheric phenomena.

## Plain Language Summary:
Part of the atmosphere's large-scale circulation results from motions that are not resolved, or partly resolved, by weather or climate models. These include internal gravity waves, with horizontal scales from a few to hundreds of kilometers. The main sources occur in the troposphere, such as flow over mountains and cloud development. Their three-dimensional propagation induces major aggregated impacts in the stratosphere and mesosphere, forcing key aspects of the circulation. This forcing is accounted for in climate models by “parameterizations,” that mimics the effect of the unresolved waves based on the large-scale, resolved flow. These parameterizations necessarily retain crude approximations and introduce significant uncertainty in the models. For gravity waves (GWs), sources are a major uncertainty. This study makes use of the high-altitude balloon campaign Strateole 2 (October 2019–February 2020). Eight balloons circled Earth at heights around 18–20 km, providing unique observations of the GWs. These are used as targets for machine learning (ML) methods that take as inputs the information from outputs of a numerical weather prediction model describing the large-scale flow. The successes and difficulties of ML provide insights which can guide improvements of parameterizations, such as the most informative large-scale variables for estimating the unresolved waves.


## Key Points:
1. Eight superpressure balloons from the Strateole 2 mission provide observations for accurate gravity wave momentum flux (GWMF) estimation
2. Three machine learning (ML) methods are employed to probe the relationship between the GWMFs and ERA5’s large-scale flows
3. The most informative large-scale inputs are provided, along with a discussion of the successes and challenges of ML methods
