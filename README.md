# ML and AI projects

Consist of various machine learning and Al projects at the experimental stage. The motive is to try simple ML projects before integrating them on the bigger
scale. The implementation are heavily based on [scikit-learn](www.scikit-learn.org), [tensorflow](www.tensorflow.org) and [Keras](https://keras.io/) 
![alt text](https://github.com/Dan-Boat/Exp.AI.ML/blob/master/img/img1.jpg?raw=True)


## 1. Stacked_ensemble
Demonstrate how to use integrated or separate stacking ensemble model for different Multi-Layer Perceptron model for simple multi-class classification probelm. The notebook uses 
sklearn datasets, tensorflow models and logistic regression form sklearn.linear model

## 2. Ensemble Regressors
Test different estimators for building ensembles trained sequentially to reduce the bias and variace of the the combined estimator. The advantage is that the individual weak models 
benefit from the high performing ones. The script uses voting regressor, which balance out the individual models weakness, and stacking regressor that uses predictions of each individual 
model to stack them together. The final estimator for stacking is optimized in cross-validation steps. Final estimators applied in this notebook includes ExtraTreeRegressor,
GradientBoosting, XGBoostRegressor, and others
The most important step is that, the ensemble model adopts different models (Beyesian regression, GLM, SVR, MLP, LassoCV, Deep Learning models) from both sklearn and tensforflow package

## 3. Hello World in ML
This repository demonstrate how to use deep learning algorithm to train the famous MNIST datasets. MNIST refers to handwritten digit recognition developed by Yann LeCun's website. The datasets contain 70,000 images (28x28 pixels) of handwriten digits (I digit per image). The goal is to write an algorithm that detects which digit is written. Since there are only 10 digits (0, 1, 2, 3, 4, 5, 6, 7, 8, 9), this is a classification problem with 10 classes.

# 4. AudioBooks target adds
This project uses client data to predict if a customer will make purchase again at an audio book shop. This information helps the shop to deploy targeted adds towards potential customers interested in their products. The model is save for future use or re-training with additional customers

# 5. Absenteeism data analysis
The project uses employees data to determine the likelyhood of certain group of people to be absent from work. This is a classification problem by predicting the level of expected leave using the personal data of the employees. In this project, I applied logistic regression since my targets where group into 0,1 representing excessively absent or moderately absent. This type of information partially help companies to target certain class of applicant for specific positions

# 6. CNN for cat or dog classification 
This project is a small exercise on using CNN to classify images of cat or dog. The dataset is large to push in this repository but can be provided upon request or downloaded from online. I used 10,000 images to train the algorithm but did not allow it to converge due to computational requirement. I used a simple architecture consisting of convolution with filters, pooling witn MaxPool2D, Flattening and then training on a dense network. 

# 7. RNN (LSTM) for Google stock price prediction
This exercise uses Long Short-Term Memory (LSTM) Recuurent Neural Network (RNN) to predict the trend of google stock price. The model is optimized on a 5 year data and independently tested on the first month of 2017. We apply a 60 timesteps for each learning point (memory range) and only rely on the stock price for the model training. 
