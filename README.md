# Assignment-19

1. What are the three stages to build the hypotheses or model in machine learning?
The three stages to build the hypotheses in machine learning are : a) Model building - This involves data preparation, training, test set generation and algorithm training b) Model testing - This involves prediction and evaluation of test data c) Applying the model - This involves deployment and monitoring of the model

2. What is the standard approach to supervised learning?
The standard approach to supervised learning is to split the set of example into the training set and the test.

3. What is Training set and Test set?
Training set - In machine learning, a training set is a dataset used to train a model. In training the model, specific features are picked out from the training set. These features are then incorporated into the model. Thereby, if the training set is labeled correctly, the model should be able to learn something from these features.

Test set - The test set is a dataset used to measure how well the model performs at making predictions on that test set. If the prediction scores for the test set are unreasonable, we’ll need to make some adjustments to our model and try again.

4. What is the general principle of an ensemble method and what is bagging and boosting in ensemble method?
Ensemble learning is used when you build component classifiers that are more accurate and independent from each other. The general principle of an ensemble method is to combine the predictions of several models built with a given learning algorithm in order to improve robustness over a single model. Bagging is a method in ensemble for improving unstable estimation or classification schemes. While boosting method are used sequentially to reduce the bias of the combined model. Boosting and Bagging both can reduce errors by reducing the variance term.

5. How can you avoid overfitting ?
By using a lot of data overfitting can be avoided, overfitting happens relatively as you have a small dataset, and you try to learn from it. But if you have a small database and you are forced to come with a model based on that. In such situation, you can use a technique known as cross validation. In this method the dataset splits into two section, testing and training datasets, the testing dataset will only test the model while, in training dataset, the datapoints will come up with the model. In this technique, a model is usually given a dataset of a known data on which training (training data set) is run and a dataset of unknown data against which the model is tested. The idea of cross validation is to define a dataset to “test” the model in the training phase.
