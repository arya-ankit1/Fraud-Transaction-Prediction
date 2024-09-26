# FraudTransactionPrediction
This project focuses on predicting fraudulent financial transactions using machine learning models. It involves data preparation, exploratory data analysis, model development, and performance evaluation using decision tree and logistic regression models.

## Project Overview
The main objective of this project is to build predictive models to identify fraudulent transactions in a large and complex financial dataset. We use both decision trees and logistic regression models to detect fraud, evaluate their performance, and implement a high-performance computational solution using Apache Spark.

### Key Features
#### Data Preparation and Cleaning:
- Loaded and cleaned a financial transaction dataset from Kaggle.
- Addressed data imbalance using under-sampling techniques.
- Prepared data for model training.

##### Exploratory Data Analysis (EDA):
- Visualized transaction amounts, transaction types, and their relation to fraud status.
- Identified patterns and key features contributing to fraudulent activities.

#### Machine Learning Models:
- Built a decision tree model for its interpretability and precision in identifying fraud patterns.
- Developed a logistic regression model using PySpark for high-performance computing and scalability.
- Balanced the dataset to enhance model performance and avoid bias.

#### Performance Evaluation:
- Compared the decision tree and logistic regression models using metrics like accuracy, precision, recall, and AUC.
- Utilized PySpark to handle large datasets efficiently and improve real-time fraud detection.

### Dataset
The dataset used in this project is sourced from Kaggle. It contains 6,000,000 transactions with 11 variables, including transaction types, amounts, balances, and fraud indicators.

#### Key Variables in the Dataset:
- step: A unit of time in the real world.
- type: Type of transaction (e.g., "CASH_IN", "TRANSFER").
- amount: The transaction amount.
- isFraud: Binary variable indicating if the transaction is fraudulent.
- isFlaggedFraud: Binary variable flagging potential fraud transactions.

#### How to Run
##### 1. Clone the repository to your local machine:
- Using link: https://github.com/your-username/Fraud-Transaction-Prediction.git

##### 2. Ensure you have the necessary dependencies installed:
- R for running the R Markdown file (tfraud.Rmd).
- Python (Jupyter Notebook) and PySpark for running the tfraud.ipynb.

##### 3. Run the analysis:
- Open the R Markdown file in RStudio to view and run the data preparation, EDA, and decision tree model analysis.
- Use Jupyter Notebook to run the logistic regression model using PySpark.

### Results and Discussion
- The decision tree model is suitable for understanding the logic behind fraud detection.
- Logistic regression using PySpark offers scalability and efficiency for handling large datasets.
- This project offers insights for improving financial fraud detection systems using machine learning.

### Future Work
- Experiment with other machine learning models like Random Forest and Gradient Boosting.
- Implement real-time fraud detection using streaming data.
- Explore additional data sources to enhance the model’s robustness.
