# 📚 Task 5: Consumer Complaint Text Classification

[![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)](https://www.python.org/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-FF9800?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/stable/)
[![NLTK](https://img.shields.io/badge/NLTK-209E9F?style=for-the-badge&logo=nltk&logoColor=white)](https://www.nltk.org/)
[![MongoDB](https://img.shields.io/badge/Data-Consumer%20Complaints-informational?style=for-the-badge)](https://catalog.data.gov/dataset/consumer-complaint-database)

This repository contains the complete solution for the Kaiburr Assessment Data Science Task, focused on building a robust Multi-Class Text Classification model.

## 🎯 Project Goal

The objective is to accurately classify raw consumer complaints into one of four specific financial product categories using NLP and machine learning:

| ID | Category Name |
| :---: | :--- |
| *0* | Credit reporting, repair, or other |
| *1* | Debt collection |
| *2* | Consumer Loan |
| *3* | Mortgage |

***

## 🛠 Execution and Analysis Flow

The solution follows a standard, rigorous data science pipeline, addressing all task requirements sequentially.

| Stage | Key Processes | Output |
| :--- | :--- | :--- |
| *1. Data Preparation (EDA)* | Filtering, cleaning, and duplicate removal. *Visualize Class Distribution* and *Text Length* statistics. | Filtered DataFrame, Two EDA Charts |
| *2. Feature Engineering* | Text cleaning, *Lemmatization, and Stopword removal. Text converted to vectors using **TF-IDF*. | Processed Narratives, Feature Matrix |
| *3. Modeling & Training* | Using a Scikit-learn Pipeline to chain preprocessing and a *Logistic Regression* classifier. | Trained Model Pipeline |
| *4. Evaluation & Prediction* | Calculation of Accuracy, Precision, Recall, and F1-score. Generation of the *Confusion Matrix*. | Evaluation Report, Predictions |

***

## 🚀 How to Run the Project

### Prerequisites
1.  *Dependencies:* Install all required libraries: pip install pandas numpy scikit-learn matplotlib seaborn nltk
2.  *Dataset:* Ensure the file **consumer_complaints.csv** is downloaded from the source and placed in the project root directory.

### Running the Script

1.  Navigate to the project directory.
2.  Execute the project
    

The script will automatically handle NLTK data downloads, display three analytical visualizations, and print the final evaluation report to the console.

