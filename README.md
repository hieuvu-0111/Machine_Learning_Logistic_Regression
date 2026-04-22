## Logistic Regression - Heart Disease dataset {-}

This notebook is adapted from a Machine Learning course assignment aiming at familiarize students with the use of Logistic Regression model supported by scikit-learn. Tasks include:

1.  **Coding Tasks:**

    1.1 Analyze the dataset using libraries like Pandas and atplotlib.  
    1.2 Preprocess the data to prepare for modeling.  
    1.3 Divide the data into training and test sets with a suitable ratio (e.g., 80/20) to ensure unbiased model evaluation.  
    1.4 Train a Logistic Regression model on the training set.    
    1.5 Evaluate the model performance on the test set using the following metrics: precision, recall, f1 score, and print out the confusion matrix.  

2.  **Open discussion questions:** 

    2.1 Is there a relationship between age and the likelihood of heart disease in this dataset? Can you explore this for different age groups?  
    2.2 How do vital signs like blood pressure and cholesterol levels compare between patients with and without heart disease?  
    2.3 Does having high fasting blood sugar appear to be a risk factor for heart disease according to this dataset?  
    2.4 Considering all the features, what features do you think might be the most important in predicting heart disease based on this dataset?  

The dataset we will be working on is 'heart-disease.csv'. It is composed of 14 attributes which are age, sex, chest pain type, resting blood pressure, serum cholesterol, fasting blood sugar, etc. This dataset is to predict, based on the given attributes of a patient, whether that particular person has a heart disease or not.
