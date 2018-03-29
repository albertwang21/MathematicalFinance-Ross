# Chapter 1. Probability


## 1. Probabilities and Events

### 1.1. Definitions
- Sample Space (*S*): the set of all possible outcomes of an experiment
- Event: any set of possible outcomes of the an experiment

### 1.2. Probabilities
- All Outcomes
![](http://latex.codecogs.com/gif.latex?p_i%5Cgeq%200%2C%20i%3D1%2C2%2C...%2Cm.)
![](http://latex.codecogs.com/gif.latex?%5Csum%20_%7Bi%3D1%7D%5Em%3D1)
- Event A
![](http://latex.codecogs.com/gif.latex?P%5Cleft%20%28%20A%20%5Cright%20%29%3D%5Csum%20_%7Bi%5Cin%20A%7Dp_i)
- The Complement of Event A
![](http://latex.codecogs.com/gif.latex?P%28A%5Ec%29%3D1-P%28A%29)
- The Union of Event A and B: Addition Theorem of Probabilities
![](http://latex.codecogs.com/gif.latex?P%28A%5Ccup%20B%29%3DP%28A%29&plus;P%28B%29-P%28AB%29)
- Conditional Probability
![](http://latex.codecogs.com/gif.latex?P%5Cleft%20%28%20A%7CB%20%5Cright%20%29%3DP%5Cleft%20%28%20AB%20%5Cright%20%29/P%5Cleft%28%20B%20%5Cright%20%29)
- The Intersection of Event A and B: Multiplication Theorem of Probabilities
![](http://latex.codecogs.com/gif.latex?P%28AB%29%3DP%28A%7CB%29P%28B%29)


### 1.3. Relations between Events
- Mutually Exclusive / Disjoint
![](http://latex.codecogs.com/gif.latex?A%5Ccup%20B%3D%5Cvarnothing)
![](http://latex.codecogs.com/gif.latex?P%28AB%29%3D0)
- Independent
![](http://latex.codecogs.com/gif.latex?P%28A%7CB%29%3DP%28A%29)


## 2. Random Variables

### 2.1. Definitions
- Random Variable: numerical quantities whose values are determined by the outcome of an experiment
- Probability Distribution: the set of the probabilities of assigning different values to an random variable
![](http://latex.codecogs.com/gif.latex?P%5Cleft%20%5C%7B%20X%3Dx_j%20%5Cright%20%5C%7D%2Cj%3D1%2C2%2C...%2Cn)
![](http://latex.codecogs.com/gif.latex?%5Csum_%7Bj%3D1%7D%5En%20P%5Cleft%20%5C%7B%20X%3Dx_j%20%5Cright%20%5C%7D%3D1)
- Bernoulli Random Variable: A random variable *X*, which is equal to 1 with probability *p* and to 0 with probability 1-*p*, is said to be a *Bernoulli* random variable with parameter *p*
- Binomial Random Variable: Considered *n* independent trials, each of which is a success with probability *p*. The random variable X, equal to the total number of successes that occur, is called a *binomial* random variable with parameters *n* and *p*

### 2.2. Expected Value
- Expected Value
![](http://latex.codecogs.com/gif.latex?E%5Cleft%5BX%20%5Cright%20%5D%3D%5Csum_%7Bj%3D1%7D%5En%20x_j%20P%5Cleft%20%5C%7B%20X%3Dx_j%20%5Cright%20%5C%7D)
- Fair Bet: *E[X]=0*
- **Formula 1**: *Y=aX+b*
![](http://latex.codecogs.com/gif.latex?E%5Cleft%5BY%20%5Cright%20%5D%3DaE%5Cleft%5BX%20%5Cright%20%5D&plus;b)
- **Formula 2**: the expected value of a sum of random variables is equal to the sum of their expected values.
![](http://latex.codecogs.com/gif.latex?E%5Cleft%5B%5Csum_%7Bj%3D1%7D%5Ek%20X_j%20%5Cright%20%5D%3D%5Csum_j%5Ek%20E%5Cleft%5BX_j%20%5Cright%20%5D)
- Expected Value of a Bernoulli Random Variable: *p*
- Expected Value of a Binomial Random Variable: *np*

### 2.3. Variance
- Variance
![](http://latex.codecogs.com/gif.latex?Var%5Cleft%28X%20%5Cright%20%29%3DE%5Cleft%5B%5Cleft%28X-E%5Cleft%5BX%20%5Cright%20%5D%20%5Cright%20%29%5E2%20%5Cright%20%5D)
- Standard Deviation: the square root of the variance
- **Formula 1**: *Y=aX+b*
![](http://latex.codecogs.com/gif.latex?Var%5Cleft%28Y%20%5Cright%20%29%3Da%5E2%20Var%5Cleft%28X%20%5Cright%20%29)
- **Formula 2**: the variance of a sum of random variables if the random variables are independent
![](http://latex.codecogs.com/gif.latex?Var%5Cleft%28%5Csum_%7Bj%3D1%7D%5Ek%20X_j%20%5Cright%20%29%3D%5Csum_%7Bj%3D1%7D%5Ek%20Var%28X_j%29)
- Variance of a Bernoulli Random Variable: *p-p^2*
- Variance of a Binomial Random Variable: *np(1-p)*

### 2.4. Covariance and Correlation
- The covariance of X and Y
![](http://latex.codecogs.com/gif.latex?Cov%5Cleft%28X%2CY%20%5Cright%20%29%3DE%5Cleft%5B%5Cleft%28X-E%5Cleft%5BX%20%5Cright%20%5D%20%5Cright%20%29%5Cleft%28Y-E%5Cleft%5BY%20%5Cright%20%5D%20%5Cright%20%29%20%5Cright%20%5D)
![](http://latex.codecogs.com/gif.latex?Cov%5Cleft%28X%2CY%20%5Cright%20%29%3DE%5Cleft%5BXY%20%5Cright%20%5D-E%5Cleft%5BX%20%5Cright%20%5DE%5Cleft%5BY%20%5Cright%20%5D)
- The covariance of independent random variables is equal to 0.
- **Formulas**
![](http://latex.codecogs.com/gif.latex?Cov%5Cleft%28X%2CY%20%5Cright%20%29%3DCov%5Cleft%28Y%2CX%20%5Cright%20%29)
![](http://latex.codecogs.com/gif.latex?Cov%5Cleft%28X%2CX%20%5Cright%20%29%3DVar%5Cleft%28X%20%5Cright%20%29)
![](http://latex.codecogs.com/gif.latex?Cov%5Cleft%28cX%2CY%20%5Cright%20%29%3Dc%5Ccdot%20Cov%5Cleft%28X%2CY%20%5Cright%20%29)
![](http://latex.codecogs.com/gif.latex?Cov%5Cleft%28c%2CY%20%5Cright%20%29%3D0)
- **Linear Property**
![](http://latex.codecogs.com/gif.latex?Cov%5Cleft%28X_1&plus;X_2%2CY%20%5Cright%20%29%3DCov%5Cleft%28X_1%2CY%20%5Cright%20%29&plus;Cov%5Cleft%28X_2%2CY%20%5Cright%20%29)
- **Generalized Linear Property**
![](http://latex.codecogs.com/gif.latex?Cov%5Cleft%28%5Csum_%7Bi%3D1%7D%5En%20X_i%2C%5Csum_%7Bj%3D1%7D%5Em%20Y_j%20%5Cright%20%29%3D%5Csum_%7Bi%3D1%7D%5En%20%5Csum_%7Bj%3D1%7D%5Em%20Cov%5Cleft%28X_i%2CY_j%20%5Cright%20%29)
- **The variance of the sum of random variables**
![](http://latex.codecogs.com/gif.latex?Var%5Cleft%28%5Csum_%7Bi%3D1%7D%5En%20X_i%20%5Cright%20%29%3D%5Csum_%7Bi%3D1%7D%5En%20Var%5Cleft%28X_i%20%5Cright%20%29&plus;%5Csum_%7Bi%3D1%7D%5En%20%5Csum_%7Bj%20%5Cneq%201%7D%20Cov%5Cleft%28X_i%2CX_j%20%5Cright%20%29)
- The correlation of *X* and *Y*: in range [-1,1]
![](http://latex.codecogs.com/gif.latex?%5Crho%5Cleft%28X%2CY%20%5Cright%20%29%3D%5Cfrac%7B%20Cov%5Cleft%28X%2CY%20%5Cright%20%29%7D%7B%5Csqrt%7BVar%5Cleft%28X%20%5Cright%20%29Var%5Cleft%28Y%20%5Cright%20%29%7D%7D)
- Given *Y=a+bX*, *\rho=1* if *b>0*, *\rho=-1* if *b<0*

### 2.5. Conditional Expectation
- The conditional expectation of *X* given that *Y=y*
![](http://latex.codecogs.com/gif.latex?E%5Cleft%5BX%7CY%3Dy%20%5Cright%20%5D%3D%5Csum_x%20xP%5Cleft%28X%3Dx%7CY%3Dy%20%5Cright%20%29)
- **The Relation between Expectation and Conditional Expectation**
![](http://latex.codecogs.com/gif.latex?E%5Cleft%5BX%20%5Cright%20%5D%3D%5Csum_y%20E%5Cleft%5BX%7CY%3Dy%20%5Cright%20%5DP%5Cleft%28Y%3Dy%20%5Cright%20%29)
![](http://latex.codecogs.com/gif.latex?E%5Cleft%5BX%20%5Cright%20%5D%3DE%5Cleft%5BE%5Cleft%5BX%7CY%20%5Cright%20%5D%20%5Cright%20%5D)


