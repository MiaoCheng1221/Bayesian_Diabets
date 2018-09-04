# Predict the onset of Diabetes based on Diagnostic Measures

### Introduction:
The objective of the project is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements like pregnancies, glucose, blood pressure, skin thickness, insulin, BMI, age. After data preprocessing, we will use MCMC, Logistic Regression, GLM, AUC to get prediction.

### Data Source:
Download the dataset from Kaggle, and link is shown below.
https://www.kaggle.com/uciml/pima-indians-diabetes-database/data

### Setup and Run:
* Platform: R studio
* Package: rstanarm, xtable, mcmc, ggplot2, pROC, caret
* Run each chunk: Command + Return

### Methods:
* Bayesian: Logistic regression
* MCMC
* AUC/ROC


### Results:
The discovery of knowledge from medical datasets is important in order to make effective medical diagnosis. Diabetes mellitus is a chronic disease and a major public health challenge worldwide. Using Bayesian methods to aid people to predict diabetes has gain major popularity. The project was proposed to predict the persons whether diabetic or not. 
There are some limitations of this study. Firstly, considering the diabetes dataset, there might be other risk factors that the data collections did not consider. According to, other important factors include gestational diabetes, family history, metabolic syndrome, smoking, inactive lifestyles, certain dietary patterns etc. MCMC is very useful for calculating posterior probability distributions, but our data volume is still very small. MCMC can be used for high-dimensional data samples, which will have more research value. The proper prediction model would need more data gathering to make it more accurate. This can be achieved by collecting diabetes datasets from multiple sources, generating a model from each dataset. Secondly, in this study we only use GLM to predict diabetes. In order to find a best prediction model, other machine learning methods such as Neural Network will be tested to compare the predicting results.

### Author
Xiaodan Chen, Xiaoyu Wang, Cheng Miao