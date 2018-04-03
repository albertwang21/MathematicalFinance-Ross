# Chapter 2. Normal Random Variable

## 2.1. Definitions
- The probability density function *f(x)* of continuous random variable *X*

![](http://latex.codecogs.com/gif.latex?P%28a%5Cleq%20X%20%5Cleq%20b%29%3D%5Cint_%7Ba%7D%5E%7Bb%7D%20f%28x%29dx)

- The p.d.f of a normal random variable with expected value ![](http://latex.codecogs.com/gif.latex?%5Cmu) 
and variance ![](http://latex.codecogs.com/gif.latex?%5Csigma%5E2)

![](http://latex.codecogs.com/gif.latex?f%28x%29%3D%5Cfrac%7B1%7D%7B%5Csqrt%7B2%5Cpi%7D%5Csigma%7De%5E%7B-%5Cfrac%7B%28x-%5Cmu%29%5E2%7D%7B2%5Csigma%5E2%7D%7D)

- A **standard normal** random variable has ![](http://latex.codecogs.com/gif.latex?%5Cmu%3D0) and 
![](http://latex.codecogs.com/gif.latex?%5Csigma%5E2%3D1)

- The standard normal distribution function of *Z* (standard normal r.v.)

![](http://latex.codecogs.com/gif.latex?%5CPhi%28x%29%3DP%5Cleft%20%5C%7B%20Z%5Cleq%20x%20%5Cright%20%5C%7D)

- Approximation function to ![](http://latex.codecogs.com/gif.latex?%5CPhi%28x%29) (ref. to p25)
- *Y* is a lognormal random variable if *X* is a normal random variable with parameters ![](http://latex.codecogs.com/gif.latex?%5Cmu) 
and ![](http://latex.codecogs.com/gif.latex?%5Csigma)
![](http://latex.codecogs.com/gif.latex?Y%3De%5E%7BX%7D)


## 2.2. Properties
- If *X* is a normal random variable then so is *aX+b*, when *a* and *b* are constants. For suppose *X* is a normal with mean 
![](http://latex.codecogs.com/gif.latex?%5Cmu) and variance ![](http://latex.codecogs.com/gif.latex?%5Csigma%5E2), then

![](http://latex.codecogs.com/gif.latex?Z%3D%5Cfrac%7BX-%5Cmu%7D%7B%5Csigma%7D%5Csim%20N%280%2C1%29)

- The sum of independent normal random variables is also a normal random variable
- The mean and variance of a lognormal random variable are

![](http://latex.codecogs.com/gif.latex?E%5BY%5D%3De%5E%7B%5Cmu&plus;%5Cfrac%7B%5Csigma%5E2%7D%7B2%7D%7D)

![](http://latex.codecogs.com/gif.latex?Var%5BY%5D%3De%5E%7B2%5Cmu&plus;%5Csigma%5E2%7D%5Cleft%28e%5E%7B%5Csigma%5E2%7D-1%20%5Cright%20%29)


## 2.3. The Central Limit Theorem
- The sum of a large number of independent random variables, all having the same probability distribution, will itself be approximately a normal random variable.
- Suppose that ![](http://latex.codecogs.com/gif.latex?X_1%2CX_2%2C...%2CX_n) is a sequence of i.i.d. random variables, each with expected value 
![](http://latex.codecogs.com/gif.latex?%5Cmu) and variance ![](http://latex.codecogs.com/gif.latex?%5Csigma%5E2), and let

![](http://latex.codecogs.com/gif.latex?S_n%3D%5Csum_%7Bi%3D1%7D%5En%20X_i)

- For large *n*, *S_n* will approximately be a normal random variable with expected value 
![](http://latex.codecogs.com/gif.latex?n%5Cmu) and variance ![](http://latex.codecogs.com/gif.latex?n%5Csigma%5E2).
As a result, for any *x* we have

![](http://latex.codecogs.com/gif.latex?P%5Cleft%20%5C%7B%20%5Cfrac%7BS_n-n%5Cmu%7D%7B%5Csigma%20%5Csqrt%7Bn%7D%7D%20%5Cleq%20x%20%5Cright%20%5C%7D%5Capprox%20%5CPhi%28x%29)









