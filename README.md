#ROP Prediction and Analysis
This repository contains code for analyzing and predicting Rate of Penetration (ROP) in drilling operations using Gradient Boosting Regressor. The dataset used for analysis is 'ROP data.csv'.
#Data Visualization
1.Line plots depicting trends of 'ROP_AVG', 'SURF_RPM', 'WOB', and 'Depth'.
2.Scatter plots illustrating relationships between different variables such as 'ROP_AVG' vs 'PHIF', 'SURF_RPM' vs 'ROP_AVG', etc.
3.Histograms showcasing the distribution of 'ROP_AVG', 'SURF_RPM', 'WOB', and 'Depth'.
4.Well log visualization for 'PHIF', 'VSH', 'SW', and 'KLOGH' variables.
5.Heatmap and pair plots to visualize correlations between different features.
#Model Training and Prediction
1.Data preprocessing including feature selection and splitting into training and testing sets.
2.Constructing a pipeline including data scaling and Gradient Boosting Regressor.
3.Evaluating the model using R2 score on both training and testing sets.
4.Predicting ROP_AVG using the trained model based on input parameters such as 'Depth', 'PHIF', 'VSH', 'SW', 'KLOGH', 'WOB', and 'SURF_RPM'.
#Optimization
Additionally, the repository provides an optimization algorithm to maximize ROP. It uses Particle Swarm Optimization (PSO) to find optimal values for input parameters ('Depth', 'WOB', 'SURF_RPM', 'PHIF', 'VSH', 'SW', 'KLOGH').
