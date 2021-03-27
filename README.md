# fGMD


This package is created exclusively for MFSGrp package. This package is a heavily modified version of gglasso that was initiated by [Yang Y.and Zou, H. (2015)](http://users.stat.umn.edu/~zouxx019/Papers/gglasso-paper.pdf). The features added to the original package: mixing parameter alpha and its net search cross validation, curvature penalizing for functional regression and its net search cross-validation, optimized Fortran core function to speed up the curvature penalization updates, progress reports and time estimations. This package does not work independently from the MFSGrp package and it does not interfere with the functions of gglasso package due to slight name differences.

## Installation

You can install   of `gglasso` from [GitHub](https://github.com/Ali-Mahzarnia/fGMD) with:

```R
install.packages("https://github.com/Ali-Mahzarnia/fGMD/blob/master/fGMD_1.0.tar.gz?raw=true",  repos = NULL, type="source")

```

