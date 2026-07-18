# Understanding the Effect of Hyperparameter Optimisation in Neural Networks

A study of how hyperparameter tuning affects feed-forward neural network
performance, using the UCI Abalone dataset.

## Overview
Simple 1–2 layer feed-forward network tuned over four hyperparameters:
neurons per hidden layer, learning rate, number of hidden layers, and
optimiser (SGD vs Adam). Statistical significance of performance differences
is assessed with paired t-tests.

## Structure
- 'Assignment_3.ipynb' - main notebook (EDA, preprocessing, training, evaluation)
- 'Assignment_3.pdf' - compiled report
- 'data' - Folder containing Abalone dataset used
- 'figures - Folder containing CSV tables and PNG figures output by the notebook
- 'latex' - Folder containing report as latex and final figures used

## Requirements
python 3 with pandas, numpy, matplotlib, seaborn, tensorflow, scikit-learn, scipy

## Data
Nash, W., Sellers, T., Talbot, S., Cawthorn, A., & Ford, W. (1994).
Abalone. UCI Machine Learning Repository. https://doi.org/10.24432/C55C7W

## Author
Sivaram Ainkaran
