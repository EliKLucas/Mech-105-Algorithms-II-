The charge on the capacitor q(t) as a function of time can be computed as:

(q0e^(-Rt/2L))*cos(((1/LC)-(R/2L)^2)^(1/2))

where:

t = time

q0 = initial charge

R = the resistance

L = inductance

C = capacitance

This MATLAB function generates a plot of this function from t = 0 to 0.8 given, q0=10, R=60, L=9, and C=0.00005. 

After this, the function creates another plot where C is 10x greater (C=0.0005).

Both plots are displayed side-by-side
