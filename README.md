# Auction Competitiveness Prediction Using Excel

## Project Overview

This project focuses on predicting whether an auction will be competitive or not using data-driven models built in Excel. A competitive auction is one in which multiple bidders actively participate, leading to a final price close to or above the market value. By analyzing historical auction data, the project aims to classify auctions as competitive or non-competitive.

## Objective

The goal of this project is to develop and compare two predictive models using Excel's Analytical Solver:
1. **Logistic Regression Model**
2. **Decision Tree Model**

These models are used to determine the likelihood of an auction being competitive, with a particular focus on testing the models against a real-world example.

## Data

The dataset used for this project includes various features relevant to auction outcomes, such as:
- **Category**: The type of item being auctioned (e.g., Clothing/Toys).
- **Currency**: The currency in which the auction is conducted (e.g., USD).
- **Duration**: The length of time the auction is active (e.g., two weeks).
- **Open Price**: The starting price of the auction (e.g., $500).
- **Seller Rating**: The reputation score of the seller (e.g., 1000).

## Methodology

### 1. Data Preprocessing
- **Data Cleaning**: Ensuring the dataset is free from missing or inconsistent entries.
- **Feature Transformation**: Converting categorical variables into numerical formats for model compatibility.

### 2. Model Building
- **Logistic Regression in Excel**: Built using the Analytical Solver to estimate the probability of an auction being competitive.
- **Decision Tree in Excel**: Developed to classify auctions into competitive or non-competitive categories.

### 3. Model Testing
Both models are tested with an example case to evaluate their performance:
- **Example Case**: 
  - **Auction Duration**: Two weeks.
  - **End Time**: Weekend.
  - **Open Price**: $500.
  - **Seller Rating**: 1000.
  - **Category**: Clothing/Toys.
  - **Currency**: USD.
  - **Result**: The product is not competitive and belongs to class 0.

### 4. Model Evaluation and Comparison

- **Accuracy**: 
  - Decision Tree: 68.27%
  - Logistic Regression: Slightly lower than the decision tree.
  
- **ROC Curve**: 
  - Decision Tree: 0.75132
  - Logistic Regression: Slightly lower performance.

- **Lift Chart**: 
  - The lift chart for the decision tree model indicates it is a better predictor for competitive items in the auction.

### Conclusion of Model Comparison
Comparing the Accuracy, ROC curve, and Lift charts of both models, the decision tree model is chosen as the better predictor for competitive items in the auction due to its superior performance across all evaluated metrics.

## Files in This Repository

- **eBayAuctions_HK.xlsx**: The Excel file containing the dataset and the models (Logistic Regression and Decision Tree).
- **Project_Report.pdf**: A detailed report outlining the project approach, methodology, results, and conclusions.

## Conclusion

This project successfully applies Excel-based analytical tools to predict auction competitiveness. The decision tree model, with its better overall accuracy and predictive power, is recommended for use in auction strategy optimization.

For a detailed explanation, please check the Project_Report.pdf.
