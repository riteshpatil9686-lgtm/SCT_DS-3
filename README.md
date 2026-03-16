# Task 03 – Decision Tree Classifier

## Objective

Build a **Decision Tree Classification model** to predict whether a customer will purchase a product or subscribe to a service based on customer attributes.

## Dataset

The task uses the **Bank Marketing Dataset**, which contains information related to bank marketing campaigns and customer demographics.

## Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Steps Performed

1. Loaded the dataset using **Pandas**.
2. Preprocessed the data and handled categorical variables using **one-hot encoding**.
3. Separated the dataset into **features (X)** and **target variable (y)**.
4. Split the data into **training and testing sets (80/20)**.
5. Trained a **Decision Tree Classifier** using Scikit-learn.
6. Evaluated the model using:

   * Accuracy Score
   * Confusion Matrix
   * Classification Report
7. Visualized the decision tree to understand the model’s decision rules.

## Output

The model predicts whether a customer will **subscribe to a term deposit** based on their profile and interaction with the marketing campaign.

## Result

Accuracy 0.8759261307088355
The Decision Tree model successfully learned patterns from the dataset and produced predictions for customer subscription behavior.
