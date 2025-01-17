---
date: 2024-04-14
description: " "
featured_image: "/images/Data_Images/king_bayesian.png"
title: "Bayesian History Matching Applied to the Calibration of a Gravity Wave Parameterization"
title2: " "
---
## Authors:
***Robert King***, ***Laura Mansfield***, and ***Aditi Sheshadri***

[Read the full paper here](https://doi.org/10.1029/2023MS004163)
## Abstract:
Breaking atmospheric gravity waves (GWs) in the tropical stratosphere are essential in driving the roughly 2-year oscillation of zonal winds in this region known as the Quasi-Biennial Oscillation (QBO). As Global Climate Models (GCM)s are not typically able to directly resolve the spectrum of waves required to drive the QBO, parameterizations are necessary. Such parameterizations often require knowledge of poorly constrained physical parameters. In the case of the spectral gravity parameterization used in this work, these parameters are the total equatorial GW stress and the half width of phase speed distribution Radiosonde observations are used to obtain the period and amplitude of the QBO, which are compared against values obtained from a GCM. We utilize two established calibration techniques to obtain estimates of the range of plausible parameter values: History matching & Ensemble Kalman Inversion (EKI).
<!--more-->
History matching is found to reduce the size of the initial range of plausible parameters by a factor of 98%, requiring only 60 model integrations. EKI cannot natively provide any uncertainty quantification but is able to produce a single best estimate of the calibrated values in 25 integrations. When directly comparing the approaches using the Calibrate, Emulate, Sample method to produce a posterior estimate from EKI, history matching produces more compact posteriors with fewer model integrations at lower ensemble sizes compared to EKI; however, these differences become less apparent at higher ensemble sizes.
## Plain Language Summary:
Atmospheric gravity waves (GWs) are buoyancy driven oscillations which propagate through the atmosphere and deposit momentum where they break. This momentum exchange plays a significant role in setting various large-scale atmospheric phenomena, of which a prominent example is the Quasi-Biennial Oscillation (QBO), a roughly 2-year oscillation of winds in the tropical stratosphere. Many of the waves responsible for creating these large scale patterns are too small to be simulated by climate models. Thus, we use parameterizations to estimate their impact on the large scale. These parameterizations have settings that require tuning, to enable the model to produce variability that matches the observed climate. In this work, we utilize and compare two techniques: History matching and Ensemble Kalman Inversion. These methods are combined with observations of the QBO to tune the settings for the GW parameterization.

## Key Points:
1. History matching and Ensemble Kalman Inversion (EKI) were used to calibrate two parameters in a gravity wave parameterization to Quasi-Biennial Oscillation observations
2. History matching was found to rapidly and compactly produce an estimate of the plausible space of parameters when compared to EKI
3. EKI was found to be strong at single best estimates of the calibrated parameters at low ensemble sizes requiring few iterations