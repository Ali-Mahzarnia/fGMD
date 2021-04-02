[![Build Status](https://travis-ci.com/Ali-Mahzarnia/fGMD.svg?branch=master)](https://travis-ci.com/Ali-Mahzarnia/fGMD)

# fGMD

This package is created exclusively for [MFSGrp](https://github.com/Ali-Mahzarnia/MFSGrp) package. This package is a heavily modified version of [gglasso](https://github.com/cran/gglasso) that was initiated by [Yang Y.and Zou, H. (2015)](http://users.stat.umn.edu/~zouxx019/Papers/gglasso-paper.pdf). The features added to the original package: mixing parameter alpha and its net search cross validation, curvature penalizing for functional regression and its net search cross-validation, optimized Fortran core function to speed up the curvature penalization updates, progress reports and time estimations. This package does not work independently from the [MFSGrp](https://github.com/Ali-Mahzarnia/MFSGrp) package and it does not interfere with the functions of gglasso package due to slight name differences.

## Installation
You can install this packege, `fGMD` from [GitHub](https://github.com/Ali-Mahzarnia/fGMD) with the R code:
``` R
install.packages("https://github.com/Ali-Mahzarnia/fGMD/archive/master.tar.gz", repos = NULL, type="source")
```
## Development version
Alternatively the development version of `fGMD` can be installed with R code:
``` R
install.packages("pacman")
pacman::p_install_gh("Ali-Mahzarnia/fGMD")
```
## Installation from source file
If the instalation fails with the above methods, install the package from the source file:
``` R
install.packages("https://github.com/Ali-Mahzarnia/fGMD/raw/master/fGMD_1.0.tar.gz",  repos = NULL, type="source")
```
