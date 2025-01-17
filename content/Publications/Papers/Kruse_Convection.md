---
date: 2024-04-16
description: " "
featured_image: "/images/Data_Images/Kruse_pub.png"
title: "Recreating Observed Convection-Generated Gravity Waves From Weather Radar Observations via a Neural Network and a Dynamical Atmospheric Model"
title2: " "
---
## Authors:
***Christopher Kruse***, ***J. Alexander***, ***M. Bramberger***, ***A. Chattopadhyay***, ***P. Hassanzadeh***, ***B. Green***, A. Grimsdell, L. Hoffmann

[Read the full paper here](https://doi.org/10.1029/2023MS003624)
## Abstract:
Convection-generated gravity waves (CGWs) transport momentum and energy, and this momentum is a dominant driver of global features of Earth's atmosphere's general circulation (e.g., the quasi-biennial oscillation, the pole-to-pole mesospheric circulation). As CGWs are not generally resolved by global weather and climate models, their effects on the circulation need to be parameterized. However, quality observations of GWs are spatiotemporally sparse, limiting understanding and preventing constraints on parameterizations. Convection-permitting or -resolving simulations do generate CGWs, but validation is not possible as these simulations cannot reproduce the CGW-forcing convection at correct times, locations, and intensities. Here, realistic convective diabatic heating, learned from full-physics convection-permitting Weather Research and Forecasting simulations, is predicted from weather radar observations using neural networks and a previously developed look-up table. 
<!--more-->
These heating rates are then used to force an idealized GW-resolving dynamical model. Simulated CGWs forced in this way closely resembled those observed by the Atmospheric InfraRed Sounder in the upper stratosphere. CGW drag in these validated simulations extends 100s of kilometers away from the convective sources, highlighting errors in current gravity wave drag parameterizations due to the use of the ubiquitous single-column approximation. Such validatable simulations have significant potential to be used to further basic understanding of CGWs, improve their parameterizations physically, and provide more restrictive constraints on tuning with confidence.

## Plain Language Summary:
Thunderstorms generate waves in the atmosphere that can generate turbulence at commercial aircraft cruising altitudes and further aloft. At these higher altitudes, they eventually break, not only generating turbulence, but also exerting forces that affect the large-scale flows in the middle atmosphere. While these waves have been known to be important since at least the 1980s, they are difficult to observe. They can be simulated, but weather models do not simulate thunderstorms in the correct locations at the right times, meaning the simulated waves cannot be directly compared against observations. Here, weather radar observations are used as input to a look-up table and a neural network to force realistic thunderstorm motions and waves within a simplified weather model. This method was able to reproduce a satellite-observed case with notable skill. In one of the first simulations of thunderstorm-generated waves comparable to satellite observations, these waves travel 100s of kilometers away from the thunderstorms, conflicting with assumptions made in weather and climate models.

## Key Points:
1. If realistic convective diabatic heating is supplied at the correct places and times, GW-resolving models can reasonably reproduce Convection-generated gravity waves (CGWs)
2. While location and type of convective storm do influence latent heating, these difference are of second order importance for CGW forcing
3. Drag due to convection-generated GWs from a compact source region is spread over O(1,000) km due to lateral propagation