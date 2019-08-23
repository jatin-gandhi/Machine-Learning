# Machine-Learning
Real World Applications 

1. Breast Cancer 

    This project creates a machine learning model which prdicts whether the cancer is malignant or benign.
    
    The dataset can be load from the scikit- learn  inbuilt datasets.
    
    Support Vector Machine is used in this project .
    
    The model can be improved by normalizing the dataset and by appropriate values of 'C' and 'gamma'.
    

2. Fashion Class Classification
    
    The project creates machine learning model which takes an image and classify the class of the image.
    
    There are total 10 classes present in the dataset .
    
    Class 0 - T-Shirt /Top
    
    Class 1 - Trouser
    
    Class 2 - Pullover
    
    Class 3 - Dress
    
    Class 4 - Coat
    
    Class 5 - Sandal
    
    Class 6 - Shirt
    
    Class 7 - Sneaker
    
    Class 8 - Bag
    
    Class 9 - Ankle Boot
    
    Link for dataset : https://sds-platform-private.s3-us-east-2.amazonaws.com/uploads/P39-Fashion-MNIST-Datasets.zip
    
    Image is represented in pixels(28 *28).
    
    CNN model is used in this project which includes various stages like feature detection / kernels followed by maxpooling and then the     result is flatten and finally passed into the neural network.
    
    The model can be improved by using the higher vaule of kernel.
    

3. Fintech Case Study

    The project creates a machine learning model which predicts whether the user will enroll to premium account or not based on the         various features of the app like number of screens ,enrolled  date , types of screens and many more.
    
    The screen_list (string) is converted into numerical columns based on the top screens and then the data is normalized.
    
    Dataset : https://sds-platform-private.s3-us-east-2.amazonaws.com/uploads/P39-CS3-Data.zip
    
    It uses the Logistic Regression model.
    
    
 4. Minimizing Customer Churn Rate
 
    The project creates a machine learning model to predict whether the customer will churn or not based on the analysis of financial       habits and this infomation can be used to minimize the churn rate .
    
    Dataset:https://sds-platform-private.s3-us-east-2.amazonaws.com/uploads/P39-Minimizing-Churn-Data.zip
    
    It uses the Logistic regression model.
    
 
 5.E-Signing Loan
 
    The project creates a machine leanring model to predict whether or not the user will get the e-loan based on the financial history.
    One Hot encoding is done to ensure that string objects are converted into numerical data.
    
    Dataset:https://sds-platform-private.s3-us-east-2.amazonaws.com/uploads/P39-Financial-Data.csv
    
    It uses Logidtic Regression model with penalty "l1" which ensures regularization .
    
    The same data is also implemented using Support Vector Machine(SVM) model .
    
    GridSearchCV is used to find the best paramneters for SVM.
    
    
 6. Credit Card Fraud Detection
 
    The project creates a deep learning model to predict whether or not the credic card transaction is fraudlent or not .
    
    The dataset contains the details about the credit card and it is anonymised by converting into equivalent numerical values.
    
    Dataset:https://sds-platform-private.s3-us-east-2.amazonaws.com/uploads/P39-Credit-Card-Fraud.zip
    
    It uses keras to make a neural network.

    
    
    
    
    
