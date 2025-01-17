---
date: 2024-07-02
description: " "
featured_image: "/images/Data_Images/karan_equations.png"
title: "Learning Closed-Form Equations for Subgrid-Scale Closures From High-Fidelity Data: Promises and Challenges"
title2: " "
---
## Authors:
***Karan Jakhar***, Yifei Guan, Rambod Mojgani, ***Ashesh Chattopadhyay***, and ***Pedram Hassanzadeh*** 

[Read the full paper here](https://doi.org/10.1029/2023MS003874)
## Abstract:
There is growing interest in discovering interpretable, closed-form equations for subgrid-scale (SGS) closures/parameterizations of complex processes in Earth systems. Here, we apply a common equation-discovery technique with expansive libraries to learn closures from filtered direct numerical simulations of 2D turbulence and Rayleigh-Bénard convection (RBC). Across common filters (e.g., Gaussian, box), we robustly discover closures of the same form for momentum and heat fluxes. These closures depend on nonlinear combinations of gradients of filtered variables, with constants that are independent of the fluid/flow properties and only depend on filter type/size. We show that these closures are the nonlinear gradient model (NGM), which is derivable analytically using Taylor-series.
<!--more-->
 Indeed, we suggest that with common (physics-free) equation-discovery algorithms, for many common systems/physics, discovered closures are consistent with the leading term of the Taylor-series (except when cutoff filters are used). Like previous studies, we find that large-eddy simulations with NGM closures are unstable, despite significant similarities between the true and NGM-predicted fluxes (correlations >0.95). We identify two shortcomings as reasons for these instabilities: in 2D, NGM produces zero kinetic energy transfer between resolved and subgrid scales, lacking both diffusion and backscattering. In RBC, potential energy backscattering is poorly predicted. Moreover, we show that SGS fluxes diagnosed from data, presumed the “truth” for discovery, depend on filtering procedures and are not unique. Accordingly, to learn accurate, stable closures in future work, we propose several ideas around using physics-informed libraries, loss functions, and metrics. These findings are relevant to closure modeling of any multi-scale system.

## Plain Language Summary:
Even in state-of-the-art climate models, the effects of many important small-scale processes cannot be directly simulated due to limited computing power. Thus, these effects are represented using functions called parameterizations. However, many of the current physics-based parameterizations have major shortcomings, leading to biases and uncertainties in the models' predictions. Recently, there has been substantial interest in learning such parameterizations directly from short but very high-resolution simulations. Most studies have focused on using deep neural networks, which while leading to successful parameterizations in some cases, are hard to interpret and explain. A few more recent studies have focused on another class of machine-learning methods that discover equations. This approach has resulted in fully interpretable but unsuccessful parameterizations that produce unphysical results. Here, using widely used test cases, we (a) explain the reasons for these unphysical results, (b) connect the discovered equations to well-known mathematically derived parameterizations, and (c) present ideas for learning successful parameterizations using equation-discovery methods. Our main finding is that the common loss functions that match patterns representing effects of small-scale processes are not enough, as important physical phenomena are not properly learned. Based on this, we have proposed a number of physics-aware metrics and loss functions for future work.

## Key Points:
1. Subgrid-scale momentum/heat flux closures discovered using common algorithms are the analytically derivable nonlinear gradient model (NGM)
2. In 2D turbulence/convection, NGM leads to unstable online simulations due to its inability to fully capture key inter-scale energy transfers
3. We suggest that physics-informed loss functions, libraries, metrics, and sparsity selections are needed to discover accurate/stable closures