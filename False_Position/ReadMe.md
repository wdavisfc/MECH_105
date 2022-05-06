## False Position Root Finding Function

This algorithm takes a function performs the false postition method for finding the roots. 

The inputs are:
1. func - the function being evaluated
2. x_i - the lower guess
3. x_u - the upper guess
4. es - the desired relative error (defaults to 0.0001%)
5. maxit - the maximum number of iterations to use (defaults to 200)

The outputs are:
1. root - the estimated root location
2. fx - the function evaluated at the root location
3. ea - the approximate percent relative error 
4. iter - how many iterations were performed
