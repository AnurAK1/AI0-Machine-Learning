# 🤖Car price prediction with Machine Learning/AI
#### 💡Project Objective
The objective of this project to generate the predictive outcomes of the car price for used vehicle.This project demonstrates my skills in data science and hands-on experience in developing machine learning models.

A Machine learning Models are developed from scratch in python for generating the prediction of the Car price. The primary package used for this prediction is `scikit-learn` (SKlearn). Re-tuning and optimisation of Algorithms was performed for generating better outcomes.
###### ⚙️Evaluation 
Root Mean Squared Error (RMSE)
The evaluation are done on the root mean squared error. RMSE is defined as:
 
$$\left(\frac{1}{N}\sum_{i=1}^{n} (y_i - \hat{y}_i)^2 \right)^{1/2}$$

where
###### $\hat{y}_i$ is the predicted value
###### $y_i$ is the actual value for each instance $i$

#### 💡Data collection and cleaning
##### 🔦Objective: Gather and preprocess the data
The Data set is sourced from Kaggle, specifically from a skills assessment challenge designed to test and develop machine learning prediction capabilities. The data is pre-cleaned and error-free.

##### 🔦Data transformation
The dataset contains extreme values for prices, so standardization is applied to normalize the data and reduce variations.

#### 💡Feature Engineering
Created new features for better understanding the data and reducing the complexities in the dataset. New features indentified might also help in increasing the performance of the model. Some of the exmaples of features that was created was car model_type(identifies the car model age), changing the transmission to number of cynlinders, Type of tansmission and Engine to HP and Number of liters etc.

#### 🤖Machine learning Modeling
Training various algorithms, including Linear Regression and Decision Trees, to identify the optimal model for car price predictions.
##### Fine-Tuning and Re-Tuning
Ensuring the best performance of our models involves:

Fine-Tuning: Adjusting hyperparameters to enhance model accuracy.
Re-Tuning: Continuously optimizing the model based on new data and performance metrics.
