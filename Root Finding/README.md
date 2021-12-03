**False Position Method:**
A function that calculates the roots of an inputed function with bracketing; roots are calculated based on a designated interval, which shifts with each interation
Inputs: (func, xl, xu, es, maxit, varargin)-
func - the function being evaluated
xl - the lower guess
xu - the upper guess
es - the desired relative error (Default set to 0.0001%)
maxit - the maximum number of iterations to use (Default value set to 200)
varargin - any additional parameters used by the function
Outputs:
root - the estimated root location
fx - the function evaluated at the root location
ea - the approximate relative error (%)
iter - how many iterations were performed
**Root Finding Method**
A box with a mass m = 25kg is being pulled by a rope. The force required to move it is given by:   
(μ*m*g)/(cos(theta)*sin(theta))

    μ = 0.55
    g = 9.81
This MATLAB script solves for theta in degrees when F = 150N. The function is then plotted with theta on the x-axis. 
This script utilizes the "bisect" function in matlab
_Information about the bisect function_
Inputs:
func - the function being evaluated
xl - the lower guess
xu - the upper guess
es - the desired relative error
maxit - the maximum number of iterations to use
Outputs:
root - the estimated root location
fx - the function evaluated at the root location
ea - the approximate relative error (%)
iter - how many iterations were performed
After calculating roots, the following values are printed in the terminal:
- root
- iter
- ea
- fx
