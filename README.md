Consumer Complaint Text Classification

This project focuses on automatically classifying consumer complaints into four categories:

Credit reporting, repair, or other

Debt collection

Consumer Loan

Mortgage

Using the Consumer Complaint Database
 from the U.S. Consumer Financial Protection Bureau (CFPB), the goal is to streamline complaint handling, improve customer support, and gain insights from large volumes of consumer feedback.

Features

End-to-end text classification pipeline

Data preprocessing with cleaning, tokenization, stopword removal, and lemmatization

Feature extraction using TF-IDF vectorization

Model training with three machine learning algorithms:

Logistic Regression

Multinomial Naïve Bayes

Linear SVM

Real-time prediction of complaint categories

Visualization of complaint distributions and confusion matrices

Workflow

Exploratory Data Analysis (EDA)

Filtering relevant data, removing null entries

Sampling 10,000 complaints for faster experimentation

Visualizing complaint distribution and text lengths

Text Preprocessing

Lowercasing, removing non-alphanumeric characters

Tokenization and stopword removal

Lemmatization

Feature Engineering

Converting text into numerical features using TF-IDF

Model Training & Selection

Train Logistic Regression, Naïve Bayes, and Linear SVM

Evaluate using accuracy, precision, recall, and F1-score

Model Evaluation

Analyze performance with confusion matrices

Compare accuracies of all three models

Prediction

Preprocess and vectorize new complaints

Predict category using the trained model

Installation

Clone this repository:




Install dependencies:

pip install -r requirements.txt


Download the Consumer Complaint Database CSV and update the file path in the notebook or script.

Usage

Run the Python script or Jupyter notebook to:

Explore the dataset

Train models

Evaluate performance

Make real-time predictions

Example:

user_input = input("Enter a consumer complaint: ")
predicted_category = predict_complaint(user_input)
print("Predicted Category:", predicted_category)

Results

Logistic Regression achieved the best accuracy

Confusion matrices help understand misclassifications

TF-IDF features combined with preprocessing improve model performance

