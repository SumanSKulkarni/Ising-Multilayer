# Notes on Monte Carlo simulations for the Ising model on multiplex networks


## ER graphs with k1 = 10, k2 = 10
r = [0, 0.5, 1, 1.5, 2, 2.5, 3, 3.5, 4, 4.5, 5]

We let the system equilibriate for 5x10^3 MC iterations.
Then, we collect statistics for 5x10^4 MC iterations. 
Once we are far away in the paramagnetic phase, we can reduce the number of iterations to 2x10^4 MC iterations.
To do this, changing niter after T > T_c + r is a good rule of thumb

   
