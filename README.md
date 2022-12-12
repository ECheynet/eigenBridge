# eigenBridge

[![View Calculation of the modal parameters of a suspension bridge on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://se.mathworks.com/matlabcentral/fileexchange/51815-calculation-of-the-modal-parameters-of-a-suspension-bridge)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3817982.svg)](https://doi.org/10.5281/zenodo.3817982)


[![Donation](https://camo.githubusercontent.com/a37ab2f2f19af23730565736fb8621eea275aad02f649c8f96959f78388edf45/68747470733a2f2f77617265686f7573652d63616d6f2e636d68312e707366686f737465642e6f72672f316339333962613132323739393662383762623033636630323963313438323165616239616439312f3638373437343730373333613266326636393664363732653733363836393635366336343733326536393666326636323631363436373635326634343666366536313734363532643432373537393235333233303664363532353332333036313235333233303633366636363636363536353264373936353663366336663737363737323635363536653265373337363637)](https://www.buymeacoffee.com/echeynet)

## Summary

The calculation of the eigenfrequencies and mode shapes of a suspension bridge using the present Matlab code is based on the theory of continuous beam and the theory of shallow cables. The mode shapes are obtained using Galerkin's method where a series expansion is used. The method was first applied by  Sigbjörnsson & Hjorth-Hansen [1]. E. Strømmen [2] expanded their works to the vertical and torsional motion.

The bridge is represented as a horizontal streamlined beam, where the z-axis is the vertical axis, the y-axis is the along-beam axis and the x-axis is the cross-beam axis. The three motions of interests (lateral, vertical, and torsional) and both symmetric and asymmetric modes are computed.

## Content:

 - eigenBridge is a function that  computes the mode shapes and eigenfrequencies of the suspension bridge
 - Documentation.mlx: is an example of the application of this function


## References:

[1] Sigbjönsson, R., Hjorth-Hansen, E.: Along wind response of suspension bridges with special reference to stiffening by horizontal cables. Engineering Structures 3, 27-37 (1981)
[2] Structural Dynamics, Einar N Strømmen, Springer International Publishing, 2013. ISBN: 3319018019, 9783319018010 Characteristics of the single-span suspension bridge
