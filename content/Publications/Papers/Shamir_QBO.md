---
date: 2023-03-26
description: " "
featured_image: "/images/Data_Images/ofer_qbo.png"
title: "The graft-versus-host problem for data-driven gravity-wave parameterizations in a one-dimensional quasibiennial oscillation model"
title2: " "
---
## Authors:
 ***Ofer Shamir***, ***David Connelly***, ***Steven Hardiman***, Zihan Shao, ***L. Minah Yang***, and ***Edwin P. Gerber***

[Read the full paper here](https://doi.org/10.1002/qj.4707)
## Abstract:
Two key challenges in the development of data-driven gravity-wave parameterizations are generalization, how to ensure that a data-driven scheme trained on the present-day climate will continue to work in a new climate regime, and calibration, how to account for biases in the “host” climate model. Both problems depend fundamentally on the response to out-of-sample inputs compared with the training dataset, and are often conflicting. The ability to generalize to new climate regimes often goes hand in hand with sensitivity to model biases. To probe these challenges, we employ a one-dimensional (1D) quasibiennial oscillation (QBO) model with a stochastic source term that represents convectively generated gravity waves in the Tropics with randomly varying strengths and spectra.
<!--more-->
We employ an array of machine-learning models consisting of a fully connected feed-forward neural network, a dilated convolutional neural network, an encoder–decoder, a boosted forest, and a support-vector regression model. Our results demonstrate that data-driven schemes trained on “observations” can be critically sensitive to model biases in the wave sources. While able to emulate accurately the stochastic source term on which they were trained, all of our schemes fail to simulate fully the expected QBO period or amplitude, even with the slightest perturbation to the wave sources. The main takeaway is that some measures will always be required to ensure the proper response to climate change and to account for model biases. We examine one approach based on the ideas of optimal transport, where the wave sources in the model are first remapped to the observed one before applying the data-driven scheme. This approach is agnostic to the data-driven method and guarantees that the model adheres to the observational constraints, making sure the model yields the right results for the right reasons.

## Plain Language Summary:
This study examines the integration of data-driven gravity-wave parameterizations into atmospheric models, highlighting challenges similar to the "graft-versus-host" problem in medicine. When these data-driven components are added to existing models, discrepancies can arise between the new parameterizations and the host model's dynamics, leading to inaccuracies. The research emphasizes the need for careful alignment between data-driven elements and traditional model structures to ensure accurate climate predictions. This underscores the importance of addressing compatibility issues when incorporating machine learning techniques into established atmospheric modeling frameworks. 
