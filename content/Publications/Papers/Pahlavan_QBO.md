---
date: 2024-07-07
description: " "
featured_image: "/images/Data_Images/hamid_qbo.png"
title: "On the importance of learning non-local dynamics for stable data-driven climate modeling: A 1D gravity wave-QBO testbed"
title2: " "
---
## Authors:
***Hamid A. Pahlavan***, ***Pedram Hassanzadeh***, and ***M. Joan Alexander***

[Read the full paper here](https://doi.org/10.48550/arXiv.2407.05224)
## Abstract:
Machine learning (ML) techniques, especially neural networks (NNs), have shown promise in learning subgrid-scale parameterizations for climate models. However, a major problem with data-driven parameterizations, particularly those learned with supervised algorithms, is model instability. Current remedies are often ad-hoc and lack a theoretical foundation. Here, we combine ML theory and climate physics to address a source of instability in NN-based parameterization. We demonstrate the importance of learning spatially non-local dynamics using a 1D model of the quasi-biennial oscillation (QBO) with gravity wave (GW) parameterization as a testbed. While common offline metrics fail to identify shortcomings in learning non-local dynamics, we show that the concept of receptive field (RF) can identify instability a-priori.
<!--more-->
We find that NN-based parameterizations that seem to accurately predict GW forcings from wind profiles (R^2≈0.99) cause unstable simulations when RF is too small to capture the non-local dynamics, while NNs of the same size but large-enough RF are stable. We examine three broad classes of architectures, namely convolutional NNs, Fourier neural operators, and fully-connected NNs; the latter two have inherently large RFs. We also demonstrate that learning non-local dynamics is crucial for the stability and accuracy of a data-driven spatiotemporal emulator of the zonal wind field. Given the ubiquity of non-local dynamics in the climate system, we expect the use of effective RF, which can be computed for any NN architecture, to be important for many applications. This work highlights the necessity of integrating ML theory with physics to design and analyze data-driven algorithms for weather and climate modeling.

## Plain Language Summary:
This study explores how machine learning (ML), particularly neural networks (NNs), can be used to model complex atmospheric phenomena like the quasi-biennial oscillation (QBO), a regular variation of winds in the tropical stratosphere. The researchers emphasize the importance of capturing non-local dynamics—interactions that occur over long distances in the atmosphere—for creating stable and accurate climate models. They demonstrate that NNs with a sufficiently large receptive field (the portion of input data the network considers) are better at learning these non-local interactions, leading to more stable simulations. This approach helps the model accurately represent the effects of gravity waves on wind patterns, which is crucial for reliable climate predictions. The findings suggest that integrating ML theory with atmospheric physics can significantly enhance data-driven climate modeling.