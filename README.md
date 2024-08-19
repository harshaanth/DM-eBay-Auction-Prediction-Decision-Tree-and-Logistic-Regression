# eBay Auction Success Prediction

## Project Description
Online auctions are a dynamic and unpredictable marketplace where various factors influence the success of a sale. In this project, we analyze historical eBay auction data to predict the outcome of an auction—whether it results in a successful sale or not. The project involves data preprocessing, feature selection, model building, and evaluation to find the most effective approach to predict auction success.

## Project Structure
- **Data Preprocessing**: The initial step involved cleaning the dataset, handling missing values, and transforming categorical features into numerical ones for model compatibility.
- **Feature Selection**: Identifying key features that significantly impact the auction outcome was crucial for improving model accuracy. Techniques like correlation analysis and feature importance from models were utilized.
- **Model Building**: Multiple machine learning models were developed, including Logistic Regression and Decision Trees. Each model was trained and evaluated to determine its effectiveness in predicting auction outcomes.
- **Model Evaluation**: The models were evaluated using metrics such as accuracy, precision, recall, and F1-score. The evaluation process helped in identifying the most reliable model for this task.

## Key Features
- **Category**: The type of item being auctioned.
- **Currency**: The currency in which the auction is conducted.
- **Duration**: The length of time the auction is active.
- **Close Price**: The final price at which the auction closed.
- **Open Price**: The starting price of the auction.
- **Competitive Auction**: A binary feature indicating whether the auction had competitive bids.

## Conclusion
This project successfully demonstrates the application of machine learning techniques to predict auction outcomes on eBay. The models developed provide insights into the factors that significantly influence auction success, offering potential improvements for sellers to optimize their listings.

## Files in the Repository
- **eBayAuctions_HK.csv**: The dataset containing historical auction data, including features like item category, currency, duration, and auction outcome.
- **Project_Report.pdf**: A comprehensive report detailing the project approach, methodologies, results, and conclusions.
