# MACHINE-LEARNING-MODEL-IMPLEMENTATION

***COMPANY*** : CODTECH IT SOLUTION

***NAME*** : SYED ARMANUL HAQUE

***INTERN ID*** : CT04DN1420

***DOMAIN*** : PYTHON PROGRAMMIN

***DURATION*** : 4 WEEKS 

***MENTOR*** : NEELA SANTOSH

****This project demonstrates how to build a spam detection model using machine learning techniques in Python, specifically using the Scikit-learn library. The goal is to classify email or SMS messages as either "spam" (unwanted) or "ham" (legitimate). The dataset used is the widely known SMS Spam Collection Dataset, available on Kaggle. It contains a large number of labeled messages categorized as spam or ham.
The process begins by importing essential libraries such as pandas and numpy for data handling, matplotlib and seaborn for visualization, and several Scikit-learn modules for preprocessing, model training, and evaluation.The dataset is loaded using pandas.read_csv(). Only the relevant columns are retained (v1 for labels and v2 for messages), and they are renamed to label and message for clarity. The labels are encoded into binary values using a simple map: 'ham' is mapped to 0 and 'spam' to 1.For handling textual data, TfidfVectorizer is used. This converts the raw text messages into numerical feature vectors based on Term Frequency-Inverse Document Frequency, emphasizing important words while down-weighting common words. This step is crucial for transforming the unstructured text into a format that machine learning models can interpret.The Logistic Regression algorithm is chosen for model training due to its efficiency and effectiveness in binary classification problems. Once trained, the model is used to predict labels on the test set.
Model evaluation is done using metrics such as accuracy score, confusion matrix, and a classification report (precision, recall, F1-score). These metrics help assess how well the model distinguishes between spam and ham messages.Finally, a custom function predict_spam() allows users to input their own message and receive a prediction—either "Spam" or "Ham"—based on the trained model.****

*Output

![Image](https://github.com/user-attachments/assets/3fc7e76c-77c1-45fb-84f3-7b4a8904d7f6)
