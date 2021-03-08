# TI84-Scripts
Various engineering scripts for Texas Instruments TI84 plus calculators

Fluid Dynamics:
* Colebrook: Iteratively solves the [Colebrook Equation](https://en.wikipedia.org/wiki/Darcy_friction_factor_formulae#Colebrook%E2%80%93White_equation) to calculate fluid flow friction factors.
* Fluidz: [Outdated] Iteratively solves the [Colebrook Equation](https://en.wikipedia.org/wiki/Darcy_friction_factor_formulae#Colebrook%E2%80%93White_equation) to calculate fluid flow friction factors.

Stress Analysis: 
* Morphs: Calculates key parameters of [Mohr's Circle](https://en.wikipedia.org/wiki/Mohr%27s_circle) for stress analysis problems.
* Stress: Combines the functionality of the Morphs and Xfrom programs. Can calculate [Mohr's Circle](https://en.wikipedia.org/wiki/Mohr%27s_circle) components, rotational transformed stress components, and principle stresses.
* Xform: Calculates stress components transformed to a specified rotated coordinate system.

Finite Element Analysis:
* Truss: Calculates the stiffness (K) matrix of an FEA truss element given the transformation values (L = cos(theta) & M = sin(theta)). 

Misc Mathematics:
* Eigen84: Finds the [eigenvalues](https://mathworld.wolfram.com/Eigenvalue.html) of an input matrix. 
* ERFS: Solves the [ERF & ERFC Functions](https://en.wikipedia.org/wiki/Error_function) for use in statistics applications.
* Interpolate: Performs linear interpolation.
* Interpolate_better: Performs linear interpolation with more user friendly options.
* Polymult: Multiplies two arbitrary length polynominals together.

# Usage

[TI Connect](https://education.ti.com/en/products/computer-software/ti-connect-ce-sw?category=overview) software is needed to open and edit these scripts. It can also be used to transfer the programs to a TI84 calculator via USB connection.

# License

![GitHub](https://img.shields.io/github/license/Grahmification/TI84-Scripts) TI84-Scripts is available for free under the MIT license.
