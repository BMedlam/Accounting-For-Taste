![image](https://github.com/brainstation-datascience/capstone-BMedlam/assets/159808208/6ff8273e-6dfa-4a21-94a7-4678d6b77f4a)

# Airbnb Property Characteristic's Annual Revnue Predictor

## Table of Contents
1. Project Overview
2. Solution Approach
3. Data
4. Notebooks
5. Conclusion

## 1. Project Overview
My name is Benedict Medlam, welcome to my capstone project for BrainStation's Data Science Diploma. 

My project title is, "Accounting for Taste". The purpose of my project is to usie machine learning to predict London property characteristics that make for a successful Airbnb rental. Success in this instance, is measured as the quantity of Annual Revenue during the Last Twelve Months (LTM).

This model will aid prospective property investors and those looking to put a new property on the airbnb market. As this model will enable property searches to be targeted more inline with customer demands.

The model will also aid existing Airbnb landlords. As through identification of property feature impact, current owners can assess what home modifications and improvements would be most beneficial in maximising their earning potential.

The model will also help the renters. As the quality of properties available should improve, with a greater focus on providing desirable amenities and being of a style which has been historically successful. 

## 2. Solution Approach

The target column for this project is the 'Annual Revenue LTM'. 

I will use a range of data preprocessing, natural language processing and machine learning methods throughout this project.

The ultimate goal has been to determine what property feature are most influencial in predicting a properties annual revenue and by how much. With features including aspects such as property type, descriptions used by the landlords, cancellation policy type, whether there is a bath or shower, what the postcode is, etc...

The two main machine learning models used in this project are Lasso modelling (Linear Regression with an L1 penalty) and XGBoost Regressors.

## 3. Data

The raw dataset can be downloaded here: https://drive.google.com/file/d/14V8xvV-zEi3BQL_vw8zzeocy-NqUCeCu/view?usp=sharing

The cleaned data, preprocessed and text embedded datasets can be found via these two links:

 - For the dataframe that has been count vectorized: https://drive.google.com/file/d/1Hxu_HE0I0w7g_RKmNiZHqZZ5hFdejpVR/view?usp=sharing
 - For the dataframe thas have been TF-IDF: https://drive.google.com/file/d/1XeJWoS6kroqZxCs8nKjkQ9Ds-lxj5F49/view?usp=sharing

## 4. Notebooks

The notebooks in order are as follows:

- Data Import and Cleaning: importing the raw data and conducting the first cleaning phase.
- EDA: gaining a more thorough understanding of the statistical relevance of the different features included in the data. 
- Preprocessing: first phase of preprocessing to prepare the data for initial modelling.
- Initial Modelling: conducted first models on numerical data, using Linear Regression, Lasso and Decision Tree Models.
- NLP: second phase of preprocessing. Processed various text columns, using a range of NLP techniques.
- Advanced Modelling: conducted further modelling on the entire processed dataframes. Using Lasso and XGBoost Regressor models.

## 5. Conclusion

The models have performed well during this project. Key features that are predictive of a higher annual revenue have been identified. 

The results could be used for prospective and existing landlords, to improve their properties market appeal, ensuring they are receiving the best possible returns on their investments. 

