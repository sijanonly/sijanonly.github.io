.. title: What are different types of gradient descent algorithm in machine learning ?
.. slug: what-are-different-types-of-gradient-descent-algorithm-in-machine-learning
.. date: 2024-05-27 22:57:35 UTC+05:45
.. tags: gradient-descent, machine-learning, machine-learning-glossary
.. category: 
.. link: 
.. description: 
.. type: text

There exist three distinct types of gradient descent learning algorithms: batch gradient descent, stochastic gradient descent, and mini-batch gradient descent.


Batch Gradient Descent (BGD)

In Batch Gradient Descent, the term 'batch' signifies the utilization of the entire training dataset during each iteration of the learning process. By incorporating all training examples for each update, Batch Gradient Descent ensures stable error gradients and a consistent trajectory towards the optimal solution, albeit with significant computational demands.
This batching method enhances computational efficiency; however, it can still result in extended processing times for large training datasets due to the necessity of storing all data in memory. While Batch Gradient Descent typically yields a stable error gradient and reliable convergence, it occasionally converges to a local minimum rather than the global optimum.


Stochastic Gradient Descent (SGD)

Stochastic Gradient Descent (SGD) enhances parameter updates by leveraging individual data points during each iteration. By conducting a training epoch for each dataset example and updating parameters sequentially, SGD minimizes memory requirements, as only a single training example needs to be stored at any given time. These frequent updates, while providing detailed and rapid adjustments, may lead to decreased computational efficiency relative to batch gradient descent. Despite the potential for noisy gradients, which arise from these frequent updates, this noise can facilitate the escape from local minima, thereby aiding in the pursuit of a global minimum. The principle of SGD is characterized by its utilization of a single example per iteration, hence the term "stochastic" reflects the random selection of each example within the batch. Given sufficient iterations, SGD proves effective, albeit with inherent noisiness.