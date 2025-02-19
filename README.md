# CS210: Introduction to Data Science - Speed Dating Analysis

## Overview

This project explores data science concepts using a dataset from a speed dating experiment. The primary goal was to analyze patterns in human decision-making and predict the likelihood of a match between two participants based on various attributes. Our approach involved data exploration, hypothesis testing, and machine learning techniques to derive meaningful insights.

For a detailed breakdown of the project’s progress, visit our blog: [CS210 Data Science Blog](https://cs210datascience.wordpress.com/)

## Dataset

The dataset contains multiple attributes related to participants, including their self-evaluated and partner-evaluated scores on attractiveness, sincerity, intelligence, fun, ambition, and shared interests. It also includes whether a match occurred between participants after the speed dating event.

## Project Breakdown

### 1. Data Exploration and Preprocessing

- Conducted an initial examination of the dataset to understand its structure.
- Visualized distributions of key features using histograms and scatter plots.
- Performed hypothesis testing to identify significant relationships between variables.

### 2. Regression Analysis

- Implemented both linear and logistic regression models.
- Found that logistic regression performed well in predicting the likelihood of a match, given its binary nature.

### 3. Machine Learning Models

We applied various machine learning techniques to classify and predict matches:

#### Decision Tree Classifier

- Chosen for its interpretability and ability to handle both numerical and categorical data.
- Implemented two models: `naive_model` and `param_model`, achieving 0.70 and 0.80 accuracy scores, respectively.
- Faced challenges with overfitting, resulting in overly complex trees that did not generalize well.

#### Random Forest Classifier

- Used to overcome the overfitting issue of decision trees.
- Achieved a 0.57 accuracy score, which was lower than decision trees but more generalized.

#### Neural Networks (Multilayer Perceptron)

- Selected for its capability to model complex, non-linear relationships.
- Achieved an accuracy of 0.68, demonstrating its effectiveness on larger datasets.
- Harder to interpret compared to decision trees.

## Conclusion

Among all models, the decision tree classifier achieved the highest accuracy (0.80). However, given the dataset's complexity and non-linear relationships, the multilayer perceptron neural network provided a more robust model. The results highlight the importance of selecting models based on both accuracy and interpretability, ensuring a balance between performance and explainability.

---

This project showcases the application of data science techniques in a real-world setting, providing insights into how human decision-making can be modeled through statistical and machine learning approaches.

