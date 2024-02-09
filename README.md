# Income Prediction from Census Data

## Project Overview
This project focuses on using machine learning to predict whether individuals earn more than $50,000 per year based on data from the 1994 U.S. Census database. The goal is to employ logistic regression to understand the impact of various demographic factors on income levels.

## Dataset
The dataset used in this project is derived from the 1994 Census database. It includes demographic features such as age, work class, education, marital status, occupation, relationship, race, sex, capital gain, capital loss, hours per week, native country, and income. The target variable is binary, indicating whether an individual's income exceeds $50,000.

## Features
The model considers the following features for predicting income:
- Age
- Workclass
- Education
- Marital Status
- Occupation
- Relationship
- Race
- Sex
- Capital Gain
- Capital Loss
- Hours per Week
- Native Country

## Preprocessing
Data preprocessing steps include:
- Converting categorical variables into dummy/indicator variables.
- Stripping whitespace from string-type columns.
- Scaling continuous variables using `StandardScaler`.

## Model
The logistic regression model was chosen for its interpretability and efficiency. The model is regularized using L1 penalty to encourage sparsity and feature selection.

## Evaluation
Model performance was evaluated using the following metrics:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC Curve and AUC

## Results
the model perform very well 

## Visualization
Several visualizations are included to aid in understanding the data and model:
- Heatmap of feature correlations.
- Bar plot of logistic regression coefficients to highlight the importance of each feature.
- ROC curve to visualize model performance.

## Conclusion
it was very good exeperience , now it's time for more models 

## How to Run
To replicate this analysis:
1. Ensure you have Python and the necessary libraries installed (`numpy`, `pandas`, `seaborn`, `matplotlib`, `sklearn`).
2. Clone this repository.
3. Run the Jupyter notebook or Python script provided.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
