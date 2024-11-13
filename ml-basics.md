# Machine Larning Section

─ [AI Foundations Course](file:./about_course.md)

## ML Basics (Supervised vs. Unsupervised, Regression vs. Classification)

Categorized in two, according to the labelled data and the traininig data sets

**Supervised**

- Requires training data with independent variables & a dependent variable (labelled data), which can be time consuming and expensive
- Need labelled data to supervise the algorithm when learning from the data

Towards...

- Regression Models
- Classification Models

**Unsupervised**

- Requires training data with independent variables only.
- No need labelled data that can "supervise" the algorithm when learning from the data.

Model must find patterns and relationships in the data without the guidance of corrected outputs. So we no longer have a dependent variable.

- Clustering Models
- Outliar Detection Models

**Regression:** Continues values.

Can be used when response variable to be predicted is a continues variable (scaler).

Examples: Linear Regression, Fixed Effects Regression, XGBoost Regression.

**Classification:** Categorical values

Different Evaluation Metrics is being used for Regression and Classification tasks.

mean-square-theor? mostly evaluate regg models while accuracy is commonly used to evaluate classification.

- RSS (Residual Sum of Squares)
- MSE (Mean Squared Error)
- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)

**RSS**

β = coefficients, yi = dependent variable, ŷ = predicted value

$$ RSS(\beta) = \displaystyle\sum_{i=1}^N (y_i - \hat{y} )^2 $$

**MSE**

Youn want to penalize large errors more than the small ones. MSE is sensitive to outliers. It might not be the best choice if the data has many outliers or extreme values.

$$ MSE = \frac 1 N \displaystyle\sum_{i=1}^N (y_i - \hat{y})^2  $$

**RMSE**

Makes it easy to interpret. Because it is in the same unit as target variable. It is commonly used when comparing performance of different models or when you want to report the error the way it easier to understand and to explain.

$$ MSE = \sqrt{MSE} = \sqrt{ \frac 1 N \displaystyle\sum_{i=1}^N (y_i - \hat{y})^2 } $$

**MAE**

To penalize all errors equally. Regardless of their magnitude. It is less sensitive to the outliers compared to MSE.

$$ MSE = \frac 1 N \displaystyle\sum_{i=1}^N |y_i - \hat{y}|  $$

**Classification Performance Metrics**

- Accuracy
- Precision
- Recall
- F-1 Score

**Accuracy**

Correct prediction is divided to all amount of predictions, means total of correct or incorrect predictions.

$$ Accuracy = \frac {CorrectPrediction} {CorrectPrediction + IncorrectPrediction} $$

**Precision**

Proposition of true predictions. It divides true positive predictions to all positive predictions.

$$ Precision = \frac {TruePositive} {TruePositive + FalsePositive} $$

**Recall**

True positive predictions among all positive prediction instances, calculated as a number of positive predictions divided by the total amount of all actual positive instances. For example we are looking into a medical test. A true positive would be a case that has correctly identified the patient as having a disease. False Positive would be the case if the correctly identifies a healthy patient as having the disease.

$$ Recall = \frac {TruePositive} {TruePositive + FalseNegative} $$

**F1 Score**

It's the harmonic mean or the usual mean of the prediction recall.

$$ F1 Score = 2 \times \frac {Recall \times Precision} {Recall + Precision} $$

**Clustering Performance Metrics**

- Homogeneity
- Silhouette Score
- Completeness

---

# `VIDEO LEFT: 59:27`

---

## Machine Learning Bias-Variance Trade-off
## Machine Learning Overfitting Regularization
## Machine Learning Linear Regression Model
## Machine Learning Linear Regression Model As a Prediction Model
## Top 10 Machine Learning Algorithms
## Data Analysis : Superstore Data Analytics Project
## Machine Learning Linear Regression Case Study
## MLOps: Movie recommendation system.
## Workshop: How to Become a Data Scientist With No Experience
## Workshop: How to Build A Startup
## Machine Learning Interview Prep🎉 Thanks to our Champion and Sponsor supporters:
