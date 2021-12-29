# Surface-Roughness-from-feed-velocity-and-depth-of-cut-using-ML-Models
I have done analysis using following details:
1) Detailed description is given for various charts and plots like scatter plot, Boxplot, Residual plot, K-value vs RMSE plot , Lasso, Ridge and Elastic-Net plot(Between Beta and Lamda values) in project report. 
2) Interpretation of results obtained by PCA is given in project report. Also,Graph is plotted between % of varition explained and Number of feature for visualisation purpose. 
3) To find whether model is overfitted or not, calculated RMSE for both train set and test set and then compare both of them to verify that model is overfitted or not. 
4) To find best parameters in Random forest regression, Gradient boosting and Decision tree regression. Parameter tuning is performed in program and is added in report. a.Random Forest: Parameters are n_estimators, max_depth, max_features per split, min_samples_split, min_samples_leaf. b.GradientBoosting : Parameters are n_estimators, max_depth, learning_rate, min_samples_leaf, min_samples_split. c.Decision Tree: Parameter is min_samples_leaf.
