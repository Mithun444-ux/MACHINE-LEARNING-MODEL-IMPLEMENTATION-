COMPANY NAME :CODETECH IT

NAME:Mithun R K

INTERN ID:CT04DG797

DURATION:08-06-2025 TO 08-07-2025

MENTOR:NEELA SANTHOSH KUMAR

DESCRIPTION:

This Python script uses machine learning (with Scikit-learn) to classify SMS messages as either "spam" or "ham" (not spam). It applies a classic text classification pipeline using the Naive Bayes algorithm, which is commonly used for spam filtering.

Steps Explained
1. Import Libraries
Essential libraries like pandas, sklearn, and numpy are imported to handle data processing, vectorization, and model training.

2. Load Dataset
The dataset is loaded from a public GitHub URL. It contains two columns:

label: either "ham" (not spam) or "spam"

message: the actual SMS text

3. Preprocess Data
Labels are converted from text to binary values: ham → 0, spam → 1

Features (X) and target labels (y) are separated

4. Train/Test Split
The dataset is split into training (80%) and testing (20%) sets to evaluate model performance on unseen data.

5. Vectorize Text
Using CountVectorizer, all messages are converted into a matrix of token counts — a basic form of feature extraction from text.

6. Train Model
A Multinomial Naive Bayes model is trained on the vectorized training data. This algorithm is ideal for text classification with word frequency features.

7. Make Predictions
The trained model is used to predict whether the test messages are spam or not.

8. Evaluate Performance
The model's accuracy, confusion matrix, and detailed classification report (precision, recall, F1 score) are printed to assess performance.

9. Custom Predictions
The script tests the model on a few custom example messages to demonstrate real-world usage.

 Purpose of the Code
To build a machine learning model that can automatically detect spam messages using natural language processing techniques and evaluate its performance effectively.

Would you like this description embedded at the top of the Jupyter notebook as a markdown cell?

OUTPUT:

![Image](https://github.com/user-attachments/assets/21cdd227-28b0-43c8-9b9b-6879a42b9d44)
