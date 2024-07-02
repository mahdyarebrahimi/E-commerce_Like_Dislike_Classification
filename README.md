# E-commerce Like Dislike Classification

This repository contains the third part of the analysis of an e-commerce dataset. The goal of this analysis task is to train classification models to predict whether a user likes or dislikes an item. This involves a standard Data Science workflow: exploring data, building models, making predictions, and evaluating results.

## Dataset

The dataset used in this analysis is a cleaned combined e-commerce sub-dataset. In this dataset, ratings have been converted to likes (score 1) and dislikes (score 0). The CSV file includes various features such as user information, timestamps, reviews, items, helpfulness scores, and more.

### Dataset Structure

The header of the CSV file is as follows:

| userId | timestamp | review | item | helpfulness | gender | category | item_id | item_price | user_city | rating |
|--------|-----------|--------|------|-------------|--------|----------|---------|------------|-----------|--------|

## Analysis Tasks

The analysis involves the following steps:

1. **Explore the Data**
   - Clean the data if necessary by removing abnormal instances and replacing missing values.

2. **Convert Features**
   - Convert object features into digit features using an encoder.

3. **Study Correlations**
   - Analyze the correlation between features.

4. **Train Logistic Regression Model**
   - Split the dataset and train a logistic regression model to predict 'rating' based on other features.
   - Evaluate the accuracy of the logistic regression model.

5. **Train KNN Model**
   - Split the dataset and train a K-Nearest Neighbors (KNN) model to predict 'rating' based on other features.
   - Evaluate the accuracy of the KNN model.

6. **Tune Hyper-parameter K in KNN**
   - Tune the hyper-parameter K in KNN to see how it influences the prediction performance.

## Notes

1. Detailed descriptions of each step are not provided in the notebook. Properly comment your notebook to make it readable.
2. You are not evaluated on the accuracy of the models but on the process used to generate them. Ensure you use both Logistic Regression and KNN models for solving this classification problem and discuss the performance of these two methods.

## How to Run

1. Clone the repository.
2. Ensure you have all necessary dependencies installed (e.g., pandas, scikit-learn, matplotlib).
3. Open the Jupyter notebook and follow the steps outlined to complete the analysis.

## Repository Structure

- `data/` : Contains the dataset used for analysis
- `notebooks/` : Jupyter notebooks with the analysis steps
- `README.md` : This file

## Conclusion

This project demonstrates the process of building and evaluating classification models to predict e-commerce ratings based on various features. The analysis highlights the importance of feature selection and model evaluation to achieve optimal performance.

