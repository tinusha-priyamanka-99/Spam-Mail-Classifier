Overview:-
This project focuses on classifying emails as spam or ham (non-spam) using natural language processing techniques and logistic regression. The dataset contains labeled emails, and the goal is to build a predictive model that can accurately classify new, unseen emails.

Contents:-
mail_data.csv: Dataset containing labeled emails.

Spam_Email_Classification.ipynb: Jupyter Notebook with the code for data preprocessing, feature extraction, model training, and prediction.

Predictive_System.py: Python script for using the trained model to classify new emails.

requirements.txt: List of Python packages required for running the code.

Data Collection & Pre-Processing
Loaded and explored the raw email dataset (mail_data.csv).
Handled missing values in the dataset.
Converted the 'Category' column to numerical values (0 for spam, 1 for ham).
Split the dataset into training and testing sets.

Feature Extraction
Used TF-IDF (Term Frequency-Inverse Document Frequency) vectorization to transform text data into numerical features.
Prepared feature vectors for both training and testing sets.

Model Training
Utilized Logistic Regression for training the classification model.
Evaluated the model's accuracy on the training set.

Model Evaluation
Predicted the labels for the test set and evaluated the model's accuracy.
Achieved high accuracy, indicating the effectiveness of the model.

Predictive System
Implemented a simple predictive system using the trained model.
Provided an example of classifying a new email as spam or ham.
