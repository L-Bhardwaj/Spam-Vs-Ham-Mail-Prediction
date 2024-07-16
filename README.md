# Spam Mail Detection using Logistic Regression

This project demonstrates how to build a spam mail detection system using logistic regression in Python.

## Dependencies

- numpy
- pandas
- scikit-learn

## Dataset

The project uses the "mail_data.csv" dataset, which contains email messages labeled as either "spam" or "ham".

## Steps

1. **Data Preprocessing:**
   - Load the dataset into a pandas DataFrame.
   - Replace null values with empty strings.
   - Encode the "Category" column using label encoding (0 for spam, 1 for ham).

2. **Feature Extraction:**
   - Use TfidfVectorizer to convert text messages into numerical feature vectors.
   - Remove stop words and convert text to lowercase.

3. **Model Training:**
   - Split the data into training and testing sets.
   - Train a logistic regression model on the training data.

4. **Model Evaluation:**
   - Calculate the accuracy of the model on both training and testing data.

5. **Prediction:**
   - Take an input email message.
   - Transform it into a feature vector using the trained TfidfVectorizer.
   - Use the logistic regression model to predict whether the email is spam or ham.

## Usage

To run the project, follow these steps:

1. Install the required dependencies.
2. Place the "mail_data.csv" file in the same directory as the notebook.
3. Execute the notebook cells in order.

## Results

The model achieves high accuracy on both training and testing data, demonstrating its effectiveness in detecting spam emails.
