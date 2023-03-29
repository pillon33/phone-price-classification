# Phone price classification.
Machine learning model that predicts phone price class.

# Dataset
In this project I used dataset available on kaggle - https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification

# Model
It's a neural network, with optimized hyperparameters using bayesian optimizer.

# Results
Using Bayesian optimization increased accuracy by ~20% which is quite a lot, final score of 73% is pretty good for such a small dataset. As shown on confusion matrix all mistakes were actually pretty close to the expected result.

# Improvments
Few things that could improve the score:
  - Bigger dataset, with NN's overfitting problems this dataset could easily lead to memorising expected results,
  - More price classes ( regression on the actual price would be the best approach to this problem ).
