---
date: 2024-01-27
description: " "
featured_image: "/images/Data_Images/hamid_qbo1.png"
title: "Explainable Offline-Online Training of Neural Networks for Parameterizations: A 1D Gravity Wave-QBO Testbed in the Small-Data Regime"
title2: " "
---
## Authors:
***Hamid A. Pahlavan***, ***Pedram Hassanzadeh***, and ***M. Joan Alexander***

[Read the full paper here](https://doi.org/10.1029/2023GL106324)
## Abstract:
There are different strategies for training neural networks (NNs) as subgrid-scale parameterizations. Here, we use a 1D model of the quasi-biennial oscillation (QBO) and gravity wave (GW) parameterizations as testbeds. A 12-layer convolutional NN that predicts GW forcings for given wind profiles, when trained offline in a big-data regime (100-year), produces realistic QBOs once coupled to the 1D model.
<!--more-->
In contrast, offline training of this NN in a small-data regime (18-month) yields unrealistic QBOs. However, online re-training of just two layers of this NN using ensemble Kalman inversion and only time-averaged QBO statistics leads to parameterizations that yield realistic QBOs. Fourier analysis of these three NNs' kernels suggests why/how re-training works and reveals that these NNs primarily learn low-pass, high-pass, and a combination of band-pass filters, potentially related to the local and non-local dynamics in GW propagation and dissipation. These findings/strategies generally apply to data-driven parameterizations of other climate processes.

## Plain Language Summary:
Due to computational limits, climate models estimate (i.e., parameterize) small-scale physical processes, such as atmospheric gravity waves (GWs), since they occur on scales smaller than the models' grid size. Recently, machine learning techniques, especially neural networks (NNs), have emerged as promising tools for learning these parameterizations from data. Offline and online learning are among the main strategies for training these NN-based parameterizations. Offline learning, while straightforward, requires extensive, high-quality data from small-scale processes, which are scarce. Alternatively, online learning only needs time or space-averaged data based on large-scale processes, which are more accessible. However, online learning can be computationally expensive. Here, we explore various learning strategies using an NN-based GW parameterization, within a simple model of the quasi-biennial oscillation (QBO), an important quasi-periodic wind pattern in the tropics. When supplied with a large 100-year data set, the offline-trained NN accurately replicates wind behaviors once coupled to the QBO model. Yet, when limited to an 18-month training data set (which is more realistic), its performance degrades. Interestingly, by online re-training specific parts of this NN using only time-averaged QBO statistics, its accuracy is restored. We term this approach an “offline-online” learning strategy. Our findings also benefit parameterization efforts for other climate processes.

## Key Takeaways:
1. 1D model of quasi-biennial oscillation (QBO) and gravity waves is used as a testbed for training neural network (NN)-based parameterizations
2. Offline training NNs in small-data regimes yields unstable QBOs that are rectified by online re-training using only time-averaged statistics
3. Fourier analysis of NNs reveals that they learn specific filters that are consistent with the dynamics of wave propagation and dissipation