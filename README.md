# DSC530-Topic-3-Build-a-Feature-Engineering-Regression-Pipeline
An assignment for DSC530 at GCU that focused on building feature engineering pipelines to streamline common processes like missing value imputation, standardization/normalization, and outlier handling.

Check out the full report [here.](https://github.com/jhould007/DSC530-Topic-3-Build-a-Feature-Engineering-Regression-Pipeline/blob/master/Build%20a%20Feature%20Engineering%20Regression%20Pipeline.ipynb)

# Assignment Instructions
1. Formulate a prediction question that you want to answer by applying regression modeling. Examples: Prediction Question: How accurately can I predict the price of a house given the values of all the variables?
2. Search and locate a dataset that is relevant to the question you created in the previous step. You may search repositories such as Data.gov, UCI Machine Learning, Kaggle, or Scikit-Learn. Find dataset with no less than 10 variables, mostly quantitative.
3. Explain and describe your dataset's variables. List your dependent and independent variables, and identify which scale is used to measure each variable (interval, ordinal, or nominal). Hint: interval is the most appropriate scale for regression analysis.
4. Import all the necessary libraries and load your dataset into a data frame.
5. Use the feature-engine transformers available in the scikit-learn library to feature engineer your dataset variables. Perform the following:
    - Missing data imputation: which transformer(s) did you apply and why?
    - Categorical variable encoding: which transformer(s) did you apply and why?
    - Outliers: which transformer(s) did you apply and why?
    - Discretization: which transformer(s) did you apply and why?
    - Variable transformation: which transformer(s) did you apply and why?
6. Split your dataset into training and testing sets.
7. Import the Pipeline class from the sklearn.pipleline library.
8. Create a pipeline object and pass all the transformers you created in step 5 and a regression model.
9. Fit the pipeline on the training dataset.
10. Make predictions and evaluate the performance of your model using the cross-validation technique. Report the RMSE and R2 values and explain the results.

APA style is not required, but solid academic writing is expected. This assignment uses a rubric. Please review the rubric prior to beginning the assignment to become familiar with the expectations for successful completion. You are not required to submit this assignment to LopesWrite.
