# Student Performance Prediction

Aim: *The task is a series of analytics questions focused on understanding the data and its relation to predicting
the target(G3 >= 10)*


Dataset: *Student performance data derived from the University of Minho, Portugal.*


# Approach:
  - Load CSV File in Pandas Dataframe
  - Check quality of Data
  - Analyze Target 'G3'
  - Simple Exploratory Data Analysis with Respect to Target 'G3'.
  - Find Correlation of Non-Categorical Variables & Plot Correlation Matrix
  - Find Correlation of Categorical Variables & Select Highly Correlated Variable.
  - Build Cascaded Linear Regression Model
  - - First Linear Model to Predict 'G1'.
  - - Second Linear Model to Predict 'G2'.
  - - Final Linear Model with input of previous predicted 'G1' & 'G2' values to Predict 'G3'. 
  - Evaluate Models by 'MAE' & 'RMSE'
  - Try some feature selection to Tune Model & compare performance with original Model.
  - Select best Models
  - Test Model on Random Data to Predict whether 'Student will Pass or Fail'.
