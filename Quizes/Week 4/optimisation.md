What is optimisation? 
The act of reducing error during the training phase. To achieve generalisation the process usually includes the minimalisation of error of validation error as well. The objective of this process is to return the most optimal weight of a classifier. (07/02)

1. 	The following are examples where numerical optimisation is used in ML (select one or more that apply):
	
- [x] Finding the optimal solution in logistic regression
- [ ] Finding the optimal solution in linear regression
- [ ] Fitting Gaussians in Gaussian Naive Bayes
- [ ] Finding the best pruning in Decision Trees

note: still wonder why it does not applied to linear regression as well, is it have a correlation of with the "continuous" parameters.

2. When we use gradient descent in well-behaved optimisation problems in machine learning. 

- [X] Unless we are already there, we will always move downhill on the error surface
- [ ] We are using the gradient of the error surface in the input feature space to decide how to change the model parameters
- [ ] Unless we are already there, we will always move in the direction of the global minimum
- [ ] Unless we are already there, we will always move in the direction of the local minimum
- [X] We are guaranteed to find a local minimum
- [X] We are using the gradient of the error surface in the model parameter space to decide how to change the model parameters
- [ ] We are guaranteed to find the global minimum

note: "well-behaved" means the learning rate is well chosen and making sure the error rate is "decreasing" on each iteration.

3. Match up the following statements that all refer to aspects of setting the step size:

- If the step size is too high -> A.
the gradient descent algorithm may oscillate
- If the step size is too low -> C.
the gradient descent algorithm will take a long time
- If the "bold driver" approach is used -> B.
successful descent steps cause the learning rate to increase slowly

4. When we are using gradient descent and update the model parameters after evaluating all training instances, it is (select all that apply):

- [ ] online gradient descent
- [ ] stochastic gradient descent
- [X] batch gradient descent

The batch gradient descent is regular gradient descent that will calculate return based on initialised learning rate in the beginning.

5. When we are using gradient descent and update the model parameters after evaluating each training instance (selected at random from all the instances), it is (select all that apply):

- [X] online gradient descent
- [X] stochastic gradient descent
- [ ] batch gradient descent

Online and stochastic gradient descent have a same meaning of randomisation. It will decide samples using uniform distribution from the total number of samples 1...N .

6. When we are using gradient descent and update the model parameters after evaluating 1% of the training instances, it is (select all that apply):

- batch gradient descent
- stochastic gradient descent
- online gradient descent

It's quite confusing when 1% terms is stated. But there is a method to apply 1% of the total sample using batch gradient descent, named "mini-batch". The online gradient descent is the typical learning of using small portion (1%) of the stream data.

7. Which of the following are true (select all that apply):

- [ ] Momentum is used to help with shallow valleys in the error surface
- [ ] Momentum is used to help with the bold driver method of gradient descent
- [X] Momentum is used to help with local minima in the error surface
- [ ] Momentum is used to help with heavy curvature in the error surface

8. If an optimisation problem is convex then which of the following are true for the surface of the objective function (select all that apply).

- [ ] it has local minima, one of which is the global minimum
- [ ] its second derivative is never positive
- [X] it has only one minimum, the global minimum
- [X] its second derivative is always positive
- [ ] its second derivative is sometimes positive and sometimes negative

Convex optimisation problems means it does not have local minima problem.

