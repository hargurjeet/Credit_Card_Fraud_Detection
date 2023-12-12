# Credit Card Fraud Detection

This project aims to detect fraudulent transactions in credit card data using machine learning. Despite the significant growth of digital transactions in India, fraudulent activities have also increased, causing losses to consumers and banks. Machine learning can play a vital role in detecting fraudulent transactions in time to prevent such losses.


## Purpose

The purpose of this project is to build a machine learning model capable of detecting fraudulent transactions. This project will also cover how to handle class imbalances present in any data set, along with model selection and hyperparameter tuning.

## Data Understanding

The data set used in this project includes credit card transactions made by European cardholders over two days in September 2013. Out of a total of 284,807 transactions, 492 were fraudulent. This data set is highly unbalanced, with the positive class (frauds) accounting for only 0.172% of the total transactions. The data set has also been modified with principal component analysis (PCA) to maintain confidentiality. Apart from "time" and "amount," all the other features (V1, V2, V3, up to V28) are the principal components obtained using PCA. The feature "time" contains the seconds elapsed between the first transaction in the data set and the subsequent transactions. The feature "amount" is the transaction amount. The feature "class" represents class labeling, and it takes the value of 1 in the cases of fraud and 0 in others.


## Usage

To use this project, you will need to have Python and the following libraries installed:

- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Imbalanced-learn

After installing the required libraries, you can run the Jupyter Notebook file "Credit_Card_Fraud_Detection.ipynb" to see the project details, including data exploration, preprocessing, model selection, and evaluation. The notebook also includes explanations of the different machine learning models used in this project and why they were chosen.

## Conclusion

This project demonstrates how machine learning can be used to detect fraudulent transactions in credit card data. It also highlights the importance of handling class imbalances and tuning machine learning models to get the best fit for the given data. We hope this project will be useful to data scientists and machine learning engineers who are interested in building fraud detection models.
