.. title: How to combat overfitting and underfitting in Machine Learning ?
.. slug: how-to-combat-overfitting-and-underfitting-in-machine-learning
.. date: 2024-06-02 15:04:06 UTC+05:45
.. tags: overfitting, underfitting, machine-learning, machine-learning-glossary
.. category: 
.. link: 
.. description: 
.. type: text

Machine Learning models learn the relationship between input (features) and output (target) using learnable parameters. The size of these parameters defines the complexity and flexibility of a given model.

There are two typical scenarios. When the flexibility of a model is insufficient to capture the underlying pattern in a training dataset, the model is called underfitted. Conversely, when the model is too flexible to the underlying pattern, it is said that the model has “memorized” the training data, resulting in an overfitted model.

Consider a system that can be explained by a quadratic function, but we use a simple line to represent it, i.e., a single parameter to capture the underlying trends in the data. Because the function lacks the required complexity to fit the data (two parameters), we end up with a poor predictor. In this case, the model will have high bias, meaning we will get consistent but consistently wrong answers. This is called an underfitted model.

Now imagine that the true system is a parabola, but we use a higher-order polynomial to fit it. Due to natural noise in the data used to fit (deviations from the perfect parabola), the overly complex model treats these fluctuations and noise as intrinsic properties of the system and attempts to fit them. The result is a model with high variance.



More details:


* `Overfitting <https://sijanb.com.np/posts/what-is-overfitting-in-machine-learning/>`_
* `Underfitting <https://sijanb.com.np/posts/what-is-underfitting-in-machine-learning/>`_