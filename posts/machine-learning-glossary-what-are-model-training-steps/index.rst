.. title: What are model training steps in machine learning ?
.. slug: machine-learning-glossary-what-are-model-training-steps
.. date: 2024-05-07 00:36:31 UTC+05:45
.. tags: machine-learning, machine-learning-glossary, training-validation-test, model-evaluation
.. category: 
.. link: 
.. description: 
.. type: text

There may exist many possible models to solve a given problem at hand. Based on your modeling decision there are usually two different ways to complete the machine learning lifecycle.

* 1st scenario. Training a single model with a training dataset and final evaluation with the test set.
* 2nd scenario. Training multiple models with training/validation dataset and final evaluation with the test set.


In case of (1st scenario), you will follow the following approach:

*  Divide the data into training and test sets. (Usually 70/30 splits)
*  Select your preferable model.
*  Train it with a training dataset.
*  Assess the trained model in the test set. (no need to perform validation in your trained model)


In case of (2nd scenario), you will follow the following approach:

*  Divide the data into training, validation, and test sets. (Usually 50/25/25 splits)
*  Select the initial model/architecture.
*  Train the model with a training dataset.
*  Evaluate the model using the validation dataset.
*  Repeat steps (b) through (d) for different models or training parameters.
*  Select the best model based on evaluation and train the best model with combined (training + validation) datasets.
*  Assess the trained model in the test set.
