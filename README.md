# 🚜 Predicting the Sale Price of Bulldozers using Machine Learning

This project aims to predict the sale price of bulldozers based on their characteristics and past sale prices. Using machine learning, we'll develop a model that can predict the future price of bulldozers in an auction setting, leveraging historical auction data.

## 1. Problem Definition

In this project, the goal is to predict the future sale price of a bulldozer, given its characteristics and previous auction sale prices of similar bulldozers. By building a machine learning model, we aim to forecast the sale price as accurately as possible, which is crucial for both buyers and sellers in the bulldozer market.

## 2. Data

The data for this project is downloaded from the Kaggle Bluebook for Bulldozers competition:  
[Bluebook for Bulldozers - Kaggle](https://www.kaggle.com/c/bluebook-for-bulldozers/data)

There are three main datasets provided:

- **Train.csv**: The training dataset, which contains data through the end of 2011. This dataset is used to train our machine learning model.
  
- **Valid.csv**: The validation dataset, which contains data from January 1, 2012 - April 30, 2012. You’ll make predictions on this set during the competition. Your score on this set contributes to the public leaderboard.

- **Test.csv**: The test dataset, which contains data from May 1, 2012 - November 2012. The results on this dataset are used to determine your final rank in the competition.

## 3. Evaluation

The evaluation metric for this competition is **RMSLE (Root Mean Squared Logarithmic Error)** between the actual and predicted auction prices.

For more information on the evaluation metric, refer to the official competition evaluation page:  
[Evaluation - Bluebook for Bulldozers](https://www.kaggle.com/c/bluebook-for-bulldozers/overview/evaluation)

### RMSLE Explanation:
The goal of most regression problems is to minimize the error between the predicted and actual values. In this project, we’ll aim to minimize the **RMSLE**, which is a common metric when dealing with skewed data (like prices). This metric helps account for relative errors in predictions, rather than absolute errors.

## 4. Features

The dataset contains a variety of features detailing the bulldozer characteristics. A full list and description of the features can be found in the [Google Sheets data dictionary](https://docs.google.com/spreadsheets/d/18ly-bLR8sbDJLITkWG7ozKm8l3RyieQ2Fpgix-beSYI/edit?usp=sharing).

## 5. Steps to Run the Notebook

1. Clone or download this repository.
2. Install the necessary dependencies. For example, using `pip`:
   ```bash
   pip install -r requirements.txt
3. Open the Jupyter Notebook (bulldozer_sales_prediction.ipynb) in your preferred IDE or Jupyter environment.
4. Run the notebook cells step by step to execute the model training, evaluation, and prediction process.
