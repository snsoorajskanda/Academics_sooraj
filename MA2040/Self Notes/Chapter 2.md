## Discrete Random Variables
![[Pasted image 20220827140716.png]]

- A random variable is called discrete if its range is either finite or countably infinite.

![[Pasted image 20220827141208.png]]

- p<sub>X</sub>(x) {PMF} = P({X= x})
- Σp<sub>X</sub>(x) = 1
![[Pasted image 20220827142949.png]]

#### The Bernoulli Random Variable
- It takes two values,1 for success and 0 for failure

![[Pasted image 20220827145101.png]]

- Combining multiple bernoulli random variables, we can construct complex random variables, like binomial RV.

#### The Binomial Random Variable

![[Pasted image 20220827145504.png]]

- Σp<sub>X</sub>(x) = 1

![[Pasted image 20220827145703.png]]

#### The Geometric Random Variable

- Eg : Suppose we toss a coin repeatedly and independently giving head with probability p, The geometric random variable is the number X of tosses needed for a head to come up for the first time
- p<sub>X</sub>(k) = (1-p)<sup>k-1</sup>p     k = 1,2....
![[Pasted image 20220827150121.png]]

#### The Poisson Random Variable

- p<sub>X</sub>(k) = e<sup>-λ</sup>λ<sup>k</sup>/k!   k = 0,1,2....
![[Pasted image 20220827150624.png]]

- It can be seen as binomial random variable with very small p and very large n. 
- λ = np
![[Pasted image 20220827150753.png]]

##### Functions of Random Variables
- Given a random variable X, one may generate other random variables by applying various transformations on X
- Y = g(X), then Y is also a random variable
![[Pasted image 20220827151208.png]]

##### Expectation
- Weighted (in proportion to probabilities) average of the possible values of X
- E(X) =  Σxp<sub>X</sub>(x)
- Mean of X can be viewed as "representative" value of X, which lies somewhere in the middle of its range (Analogy : Centre of Gravity)
- If PMF is symmetric around a certain point, that point must be equal to the mean

##### Variance, Moments,standard deviation and the Expected Value Rule
- Second moment of random variable X is defined as the Expected value of X<sup>2</sup> 
- nth moment is defined as E(X<sup>n</sup>)

- Variance is defined as
var(X) = E{(X - E(X))<sup>2</sup>}
- Variance is always non-negative

- Standard deviation : Easier to interpret as it has same units as X
σ<sub>x</sub> = (var(X))<sup>1/2</sup>

![[Pasted image 20220827152916.png]]

- E(X<sup>n</sup>) = Σ x<sup>n</sup>p<sub>X</sub>(x)
- var(X) can be zero for p<sub>X</sub>(x) > 0 , if x = E(X)

##### Properties of mean and variance
- Y = aX + b ;E(Y) = aE(X) + b; var(Y) = a<sup>2</sup>var(X)
![[Pasted image 20220827153701.png]]

- Unless g(X) is linear function, it is not generally true that E(g(X)) is equal to g(E(X))

##### Mean and Variance of some common Random Variables

- Bernoulli random variable
![[Pasted image 20220827154244.png]]

- Discrete Uniform Random Variable
![[Pasted image 20220827154416.png]]

![[Pasted image 20220827154441.png]]


- Poisson Random Variable
![[Pasted image 20220827154628.png]]

- Read the quiz problem(pg 91-92 of tb)

##### Joint PMFs of Multiple Random Variables

- p<sub>X,Y</sub>(x,y) = P(X = x, Y= y)
- If A is a set of all the pairs (x,y) that have a certain property, then

P((X,Y)**∈**A) = Σp<sub>X,Y</sub>(x,y) such that (x,y)**∈**A

p<sub>X</sub>(x) =  Σp<sub>X,Y</sub>(x,y) over y

- p<sub>X</sub> and p<sub>Y</sub> are referred to as marginal PMF to distinguish them from joint PMF

- Z = g(X,Y)
![[Pasted image 20220828102452.png]]
![[Pasted image 20220828102514.png]]
![[Pasted image 20220828102549.png]]

###### More than 2 RV
![[Pasted image 20220828102749.png]]
![[Pasted image 20220828102805.png]]

##### Conditioning a random variable on an event
![[Pasted image 20220828104452.png]]
![[Pasted image 20220828104550.png]]

![[Pasted image 20220828105201.png]]
![[Pasted image 20220828105335.png]]

![[Pasted image 20220828110404.png]]
