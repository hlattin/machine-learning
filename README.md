# machine-learning
This repo is for machine-learning practice


Supervised Learning:: Learn from Data labeled with the right answers
1.) Regression to predict a number of infinitely many possible outputs.
2.) Classification to predict categories with a small number of possible outputs.

Unsupervised Learning: There is no Y value to label the data. We are looking for a pattern within the data. 
1.) Clustering: Grouping a bunch of data together. Looking for patterns (grouping customers for growing skills, developing career, or staying up to date with ai).
2.) Anomaly detection: Find unusual data points
3.) Dimensionality reduction: Compress data using fewer numbers

Linear Regression: Supervised learning model that you train by giving data. It is a Regression model, because it perdicts numbers as the output. Infine possible numbers this model could output
1.) Training Set: X(feature), Y(prediction) and Index for Rows
2.) Learning Algorithm: X (Feature) - > F (Model) - > Y (Prediction)
3.) F w,b (x) = wx + b
4.) Univariate linear regression: the size is one variable (feature) x



![image](https://github.com/user-attachments/assets/ee7c3cc4-66aa-4349-99d5-219c8c346e91)


Cost Function: Tells us how well the model is doing. W and B are called the parameters. The variables you can adj during training to improve the model (weights, and coefficient). 
- F(X) = w x + b
- We want to align the parameters as close as we can to the training example.
- How do we find values for W and B to get close to the targets for x and y
- Construct a cost function: takes y hat and compares it to the target y (Yhat - y)^2
- <img width="1200" height="594" alt="image" src="https://github.com/user-attachments/assets/835a364d-9555-4556-adb4-393c89f342a8" />
- we want to find values where w and b make the cost function small.
