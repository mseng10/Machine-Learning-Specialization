Supervised learning - learns from being given "right answers"
Regression - predict a number infinitely many possible outcomes (categories)
Classification - predict a finite output


Unsupervised Learning - no labels y, we don't kno

Training Set - Data used to train the model
x input - feature
y  output - target
m - numver of training examples
(x, y) = single training example
(x^i, y^i) = ith training example (1 row) - not exp duhhh



linear regression

 + y_hat = estimate
 + y = target

 + f(x) = wx + b

 + 1 variable = linear w

cost function 
 + how well the model is doing
 + y_hat - y = error, how har off

 + (1/2m)sum(i...m)(y_hat -h)^2 - cost function (squared error cost function)

  + goal is to minimize J(w,b) - essentially make the difference near 0

![Alt text](./assets/cost.png)

Gradient Descent - minminze cost
 + w = w - alphaa * d/dxJ(w,b)
 + alpha - learning rate (if too small then the alg. will take too long, if too large, we can overshoot)
 + d/dxJ(w,b) - learning rate (size of steps and direction we go)
  + repeat until convergence

Batch GD - each step of gd uses all the training examples

