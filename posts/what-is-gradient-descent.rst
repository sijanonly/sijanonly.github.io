.. title: What is gradient descent ?
.. slug: what-is-gradient-descent
.. date: 2024-05-11 12:47:15 UTC+05:45
.. tags: gradient-descent, machine-learning, machine-learning-glossary
.. category: 
.. link: 
.. description: 
.. type: text



Short:

Gradient descent is an optimization algorithm used to determine the coefficients / parameters of a function (f) that minimize a cost function.

`reference <https://machinelearningmastery.com/gradient-descent-for-machine-learning/>`_


Detail:


Gradient descent is a widely used optimization approach for training machine learning models and neural networks. Optimization is the process of minimizing or increasing an objective function.
Optimization entails calculating the gradient (partial derivatives) of the cost function for each parameter (weights and biases). To do this, the models are given training data iteratively.
And, the gradient points are determined. The gradient consistently indicates the direction of the steepest increase in the loss function. The gradient descent algorithm proceeds by taking a step in the direction of the negative gradient to minimize the loss as efficiently as possible.


* The selection of the learning rate has a substantial influence on the effectiveness of gradient descent. An excessively high learning rate may cause the algorithm to overshoot the minimum, while an excessively low learning rate may result in prolonged convergence times.
* Due to its non-convexity, the loss function L(w) of a neural network is generally known to potentially have multiple local minima. When multiple local minima are present, it is highly likely that the algorithm may fail to converge to a global minimum. Thus, local minima pose significant challenges as they may cause the training process to stall rather than progress towards the global minimum.
* Gradient descent, despite being a widely utilized optimization algorithm, does not ensure convergence to an optimum in all scenarios. Various factors can hinder convergence: Saddle Points: In high-dimensional spaces, gradient descent may become trapped at saddle points where the gradient is zero but does not correspond to a minimum.
* Saddle points in a multivariable function are critical points where the function does not achieve either a local maximum or a local minimum value. 
* A common issue with both local minima and saddle points is the presence of plateaus with low curvature in the error landscape. Although gradient descent dynamics are repelled from a saddle point towards lower error by following directions of negative curvature, this repulsion can be slow due to the plateau.
* Stochastic Gradient Descent (SGD) can occasionally escape simple saddle points if fluctuations occur in different directions and the step size is sufficiently large to overcome the flatness. However, saddle regions can sometimes be quite complex.
* The gradient of error, defined over the difference between the actual and predicted outputs, approaches zero at a local minimum, causing progress to stall due to weight correction steps being proportional to the gradient's magnitude, which is near zero at a minimum. Techniques such as 'random weight initiation' can be employed to avoid this issue.


