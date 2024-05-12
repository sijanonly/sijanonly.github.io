.. title: What is overfitting in Machine Learning ?
.. slug: what-is-overfitting-in-machine-learning
.. date: 2024-05-12 17:38:25 UTC+05:45
.. tags: overfitting, high-variance, machine-learning, machine-learning-glossary
.. category: 
.. link: 
.. description: 
.. type: text

Overfitting occurs when the model attempts to match the training set too closely. On fresh data, the overfitted model is unable to produce accurate predictions.

Important details:

1. The model will attempt to match the data too closely and will pick up on noise in the data when the training data set is limited or the given model is complex.
2. An overfitted model picks up patterns that are unique to the training set and overlooks the generic patterns.
3. Regularization can reduce overfitting.
4. Overfitting can also be decreased by training on a large and diversed training data points.
5. Overfitting can be detected by high variation .i.e, if the test data has a high error rate while the training data has a low error rate.
6. A high variance model will overfit the data and is flexible in capturing every detail—relevant or not—and noise in the data.
7. A high variance model is also indicated as: Training error << Validation error.
8. More training data will improve the generalization of the given model and avoids overfitting.