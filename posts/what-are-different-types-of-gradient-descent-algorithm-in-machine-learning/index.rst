.. title: What are different types of gradient descent algorithm in machine learning ?
.. slug: what-are-different-types-of-gradient-descent-algorithm-in-machine-learning
.. date: 2024-05-27 22:57:35 UTC+05:45
.. tags: gradient-descent, machine-learning, machine-learning-glossary
.. category: 
.. link: 
.. description: 
.. type: text

There exist three distinct types of gradient descent learning algorithms: batch gradient descent, stochastic gradient descent, and mini-batch gradient descent.


Batch Gradient Descent

In Batch Gradient Descent, the term 'batch' signifies the utilization of the entire training dataset during each iteration of the learning process. By incorporating all training examples for each update, Batch Gradient Descent ensures stable error gradients and a consistent trajectory towards the optimal solution, albeit with significant computational demands.
This batching method enhances computational efficiency; however, it can still result in extended processing times for large training datasets due to the necessity of storing all data in memory. While Batch Gradient Descent typically yields a stable error gradient and reliable convergence, it occasionally converges to a local minimum rather than the global optimum.
