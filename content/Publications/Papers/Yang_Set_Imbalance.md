---
date: 2024-02-28
description: " "
featured_image: "/images/Data_Images/Minah.png"
title: "Overcoming set imbalance in data driven parameterization: A case study of gravity wave momentum transport"
title2: " "
---
## Authors:
***L. Minah Yang*** and ***Edwin P. Gerber***

[Read the full paper here](https://doi.org/10.48550/arXiv.2402.18030)
## Abstract:
Machine learning for the parameterization of subgrid-scale processes in climate models has been widely researched and adopted in a few models. A key challenge in developing data-driven parameterization schemes is how to properly represent rare, but important events that occur in geoscience datasets. We investigate and develop strategies to reduce errors caused by insufficient sampling in the rare data regime, under constraints of no new data and no further expansion of model complexity. Resampling and importance weighting strategies are constructed with user defined parameters that systematically vary the sampling/weighting rates in a linear fashion and curb too much oversampling.
<!--more-->
Applying this new method to a case study of gravity wave momentum transport reveals that the resampling strategy can successfully improve errors in the rare regime at little to no loss in accuracy overall in the dataset. The success of the strategy, however, depends on the complexity of the model. More complex models can overfit the tails of the distribution when using non-optimal parameters of the resampling strategy.

## Plain Language Summary:
Subgrid-scale parameterizations are a part of climate models that represent effects of processes that cannot be directly modelled. In recent years, there have been many efforts to improve upon these parameterizations by applying machine learning techniques. Since these methods rely heavily on the dataset they are learning from, it is important
to consider the frequency at which important events occur within the dataset because they are adept at learning frequent events at high accuracy but are prone to learning rare but important events at low accuracy. To remedy this data imbalance problem, we developed a resampling methodology that can be easily adjusted by tuning just two parameters. We find that a right combination of those parameters can improve the accuracy of an ML model at the rare event regime while keeping the accuracy high in the frequent regime. However, a “wrong” combination can actually increase the errors at the rare event regime by overfitting to that regime.

## Key Points:
1. Unresolved geophysical processes often exhibit long tail distributions, which leads
to imbalanced datasets for data-driven parameterizations.
2. Two strategies to overcome data imbalance are presented, where either the sampling or loss function is modified to better capture the tails.
3. Proof of concept is demonstrated by using a wind range metric to improve a machine learning emulator of a physics based gravity wave parameterization.