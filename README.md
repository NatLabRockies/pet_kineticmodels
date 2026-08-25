SWR 26-087 "Kinetic Model of HoxEFU reduction by NADH"

This code will simulate the reduction of HoxEFU by NADH. The electro transfer rate constants for the simulation are specified in the .csv files. The two .csv files correspond tot he two models described in Dawson et al. Cell. Rep. Phys. Sci. 2026.

The code utilizes a chemical master equation, a set of differential equations, defining the time evolution of the oxidation and reduction kinetics of NAD+, NADH, a FMN flavin, and a set of iron sulfur clusters. The kinetics of HoxEFU reduction by NADH are evaluated by numerical integration of the chemical master equation using a variable-time-step Runge-Kutta algorithm.

The code is run as follows,

python run_kinetics_v2.py
