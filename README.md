# -House-Price-Prediction-
Using Multiple linear regression model to predict median house prices 
# Regression Analysis Project (Exploratory ML Practice)

##  Project Overview
This project is a practice-based machine learning workflow created to understand the **end-to-end process of building a regression model**, starting from data exploration to model saving.
The primary goal of this project is **learning and self-evaluation**, rather than deployment or real-world clinical decision-making.

##  Objective
- Perform Exploratory Data Analysis (EDA)
- Apply feature engineering
- Train regression models
- Check basic model assumptions using visualizations
- Save the trained model for reuse (model pickling)

## Dataset
The dataset is imported from a standard machine learning library and contains multiple numerical features suitable for regression analysis

## Exploratory Data Analysis (EDA)
EDA was performed to:
- Understand feature distributions
- Study pairwise relationships between variables
- Identify potential patterns and correlations
Visualization techniques such as pair plots and distribution plots were used.

## Feature Engineering
Basic feature engineering steps were applied to:
- Prepare the data for modeling
- Improve model interpretability
- Ensure compatibility with regression assumptions

## Model Training
A regression model was trained using selected features.
The training process involved:
- Splitting data into training and testing sets
- Fitting the model on training data
- Generating predictions
- 
##  Model Assumption Checks
Regression assumptions were checked using visual diagnostics:
- Linearity
- Residual distribution
- Normality of errors
Although the assumptions were not perfectly satisfied, the model performance was found to be **acceptable for a learning-based project**.

##  Model Pickling
The trained model was saved using Python’s `pickle` module so that it can be reused later without retraining.
This step was included to understand:
- Model persistence
- Reusability in practical workflows

##  Key Learnings
- How to structure an end-to-end ML notebook
- Importance of EDA before modeling
- Role of assumptions in regression analysis
- Practical usage of model serialization

## Limitations
- Dataset is small and used only for practice
- No hyperparameter tuning was performed
- Model is not intended for real-world decision-making
- Results should not be interpreted as causal

## Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Status
✔ Completed as a **learning and practice project**  
✔ Open for future improvements

## 🙌 Note
This project was created for **self-learning and conceptual clarity** in machine learning and regression analysis.
