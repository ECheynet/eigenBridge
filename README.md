# eigenBridge

[![View Calculation of the modal parameters of a suspension bridge on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://se.mathworks.com/matlabcentral/fileexchange/51815-calculation-of-the-modal-parameters-of-a-suspension-bridge)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3817982.svg)](https://doi.org/10.5281/zenodo.3817982)


## Summary

The calculation of the eigenfrequencies and mode shapes of a suspension bridge using the present Matlab code is based on the theory of continuous beam and the theory of shallow cables. The mode shapes are obtained using Galerkin's method where a series expansion is used. The method was first applied by  Sigbjörnsson & Hjorth-Hansen [1]. E. Strømmen [2] expanded their works to the vertical and torsional motion.

The bridge is represented as a horizontal streamlined beam, where the z-axis is the vertical axis, the y-axis is the along-beam axis and the x-axis is the cross-beam axis. The three motions of interests (lateral, vertical, and torsional) and both symmetric and asymmetric modes are computed.

## Content:

 - eigenBridge is a function that  computes the mode shapes and eigenfrequencies of the suspension bridge
 - Documentation.mlx: is an example of the application of this function


## References:

[1] Sigbjönsson, R., Hjorth-Hansen, E.: Along wind response of suspension bridges with special reference to stiffening by horizontal cables. Engineering Structures 3, 27-37 (1981)
[2] Structural Dynamics, Einar N Strømmen, Springer International Publishing, 2013. ISBN: 3319018019, 9783319018010 Characteristics of the single-span suspension bridge
