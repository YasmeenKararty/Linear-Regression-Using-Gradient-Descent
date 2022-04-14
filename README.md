# Linear Regression Using Gradient Descent

This notebook works on applying Linear Regression using Gradient Descent Algorithm to predict Weight of fish.

# Gradient Descent Algorithm: 
```
Input: Y,theta, X, alpha, tolerance, max iterations
Output: theta

for i = 0; i < max iterations; i++  do
    current cost = Cost(Y, X, theta) 
    
    if current cost < tolerance then
       break
    
    else
      gradient = Gradient(Y. X. theta)
      theta(j) = theta(j) - alpha * gradient;
      
```

# The output:
A graph showing the loss every 10 epochs

![AssignmentOutput](https://user-images.githubusercontent.com/66736704/163467522-a7581ec1-7c3b-45af-bc32-aa46941e2eae.png)
