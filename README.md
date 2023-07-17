
# Credit-Card-Fraud-Detection
- This project focuses on detecting of credit card fraud. The project includes machine learning, exploratory data analysis (EDA), and data visualization techniques to gain insights into the dataset and understand its patterns. The project uses the creditcard.csv dataset, which can be downloaded from Kaggle: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud


#### NOTE:Beacuse of the dataset is too large I couldn't upload the dataset here. That's why you have to download it from Kaggle.
# ACKNOWLEDGEMENTS

### DATA CONTENT
- The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

- It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.
 

## Installation
The following tools were used for this analysis:

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scipy
- Sklearn
- Xgboost
- Lightgbm
- Catboost

- To run this project, you will need to have Python 3 installed on your machine. You can install the required libraries by running the following command:


- pip install pandas matplotlib seaborn numpy plotly Sklearn Xgboost Catboost Lightgbm
## Usage 
- To run the analysis, simply execute the notebook. The script will generate several visualizations that help illustrate analysis of data.
## Roadmap

[1. IMPORTING LIBRARIES](#1)
    
[2. LOADING DATA](#2)  

[3. DATA CONTENT](#3)

[4. EXPLORATORY DATA ANALYSIS](#4)

[5. DATA VISUALIZATION](#5)

[6. DATA PREPROCESSING](#6)     

[7. MODEL TRAINING AND EVALUATING](#7)

[8. FEATURE IMPORTANCE](#8)

[9. PCA VISUALIZATION](#9)

[10. AUC-ROC CURVE](#10)

[11. CONCLUSION](#11)


 The analysis includes visualizations using Matplotlib, Plotly and Seaborn.

## Contributing

- Contributions to this project are welcome. If you notice any errors or have ideas for additional analyses, please feel free to open an issue or submit a pull request.


## Conclusion 

* I investigated the data, checking for data unbalancing, visualizing the features and understanding the relationship between different features. We then investigated ten predictive models. The data was split in 2 parts, a train set and a test set.

* I have evaluated the performance of the models using the AUC-ROC curve and other metrics. The best results were obtained with XGBoost, with an AUC score of 0.97 and a accuracy of 0.9996.

