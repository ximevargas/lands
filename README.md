# lands
This repository is a fork of the **RAM Parabolic Equation Code** written in Fortran
95 code at the University of Washington. It uses a version of Mike Collins' RAM 
PE solution for long range acoustic calculations. It is directly derived from the 
MATLAB code developed by Matt Dzieciuch, and includes MPI capabilities.

The original source code was downloaded from the following website:
<http://staff.washington.edu/dushaw/AcousticsCode/RamFortranCode.html>

This fork was originally built directly from the code found at that website.
This fork is meant to track any changes made by the BYU Acoustics Research group
and is not intending to replace the project.

The original software did not include a license, so a GNU v3 license was added
and the following copyright statement from the original work is included here:

```
Copyright © 2008-2015 by the contributing authors. All material on this collaboration platform is the property of the contributing authors. 
```

## Documentation

Original documentation can be found at the [University of Washington website](http://staff.washington.edu/dushaw/AcousticsCode/RamFortranCode.html).

## Changes Made In this Fork

- This README
- Link the Makefile to the proper `gfortran` compiler located in a `/usr/local/bin` directory
- More to come?
