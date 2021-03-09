# PHSX815_Week5 
HW5: I am sampling from the Sigmoid function 1/(1 + e^x)
HW6: I am integrating function np.exp(x**3)

## This repository contains several types of programs:
* `SigmoidSampling.py` 
* `Random.py`
* `CalculatePi.py` and `GaussRandom.py` are example code provided by Prof.Rogan in class
* `numerical_integration.py`
* `ImplementedSampling.pdf` and `DiffvsN_integration.pdf` are the final pdf plots for two practice (HW5 & HW6)

## General info
This repository will include HW5 and HW6 practice 
* HW5 - using the rejection sampling method to sampling from a distributino and visualize the target distribution, proposal distribution and random samples.
* HW6 - implement two different numerical integration methods - trapezoidal rule and Gaussian quadrature, to integrate selected function. Compare the difference between the two numerical integrals, and their difference with the correct/analytic answer, as a function of the number sub-intervals. 

## Code Usage
* Can be run from the command line using the `-h` flag to display usage options. 
* e.g `SigmoidSampling.py`
`python SigmoidSampling.py -Nsample [number] -range [Xmax]`
`Nsample` is specified for number of samples from the target distribution, `range` is specified when to change the range of x values from the sampling.
* e.g `numerical_integration.py`
`python numerical_integration.py -N [number of intervals] -a [lower bound of integration] -b [upper bound of integration]`

  
