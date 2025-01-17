---
date: 2024-08-01
description: " "
featured_image: "/images/Data_Images/chew_unstructured.png"
title: "A Constrained Spectral Approximation of Subgrid-Scale Orography on Unstructured Grids"
title2: " "
---
## Authors:
***Ray Chew***, Stamen Dolaptchiev, Maja-Sophie Wedel, and ***Ulrich Achatz***

[Read the full paper here](https://doi.org/10.1029/2024MS004361)
## Abstract:
The representation of subgrid-scale orography is a challenge in the physical parameterization of orographic gravity-wave sources in weather forecasting. A significant hurdle is encoding as much physical information with as simple a representation as possible. Other issues include scale awareness, that is, the orographic representation has to change according to the grid cell size and usability on unstructured geodesic grids with non-quadrilateral grid cells. This work introduces a novel spectral analysis method approximating a scale-aware spectrum of subgrid-scale orography on unstructured geodesic grids.
<!--more-->
The dimension of the physical orographic data is reduced by more than two orders of magnitude in its spectral representation. Simultaneously, the power of the approximated spectrum is close to the physical value. The method is based on well-known least-squares spectral analyses. However, it is robust to the choice of the free parameters, and tuning the algorithm is generally unnecessary. Numerical experiments involving an idealized setup show that this novel spectral analysis performs significantly better than a straightforward least-squares spectral analysis in representing the physical energy of a spectrum. Studies involving real-world topographic data are conducted, and reasonable error scores within ±10% error relative to the maximum physical quantity of interest are achieved across different grid sizes and background wind speeds. The deterministic behavior of the method is investigated along with its principal capabilities and potential biases, and it is shown that the error scores can be iteratively improved if an optimization target is known. Discussions on the method's limitations and broader applicability conclude this work.

## Plain Language Summary:
Wind flow over terrain has wide-ranging influences on atmospheric processes. Meteorologists want to include this effect in their weather forecasts but encounter computational limitations. For global weather forecasting, terrain features are relatively small and usually not explicitly represented in forecast models. An ongoing research question is how best to represent these small-scale features in forecast models. However, a few difficulties arise: (a) We want to encode as much information about the terrain with as simple a representation as possible. (b) Some forecast models represent the globe with an icosahedron. Therefore, terrain information must be encoded within the triangular or hexagonal cells. (c) The information encoded has to change if the size of the triangles or hexagons changes. In this work, we present a novel method to overcome the three difficulties mentioned above. We can compress terrain information from over 50,000 to below 100 data points that can be used for climate simulations. When the relative effect of the encoded terrain on atmospheric processes is considered, the method has good accuracy despite the severe constraints and data compression, with a 10% error bound. Apart from representing terrain in weather forecasting, this method has potential applications for generic data analysis.

## Key Points:
1. We introduce a novel scale-aware spectral approximation method for subgrid-scale orographic data on non-quadrilateral geodesic grids
2. The method yields physically sound results and achieves reasonable error scores when approximating real-world orographic spectra
3. The method features over two orders of magnitude compression in complexity and has potential applications in generic spectral analyses