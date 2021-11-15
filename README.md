# Building-a-model-that-can-predict-if-a-student-can-be-admitted-into-the-institution-or-not-
Every year thousands of applications are being submitted by international students for admission in colleges of the USA. It becomes an iterative task for the Education Department to know the total number of applications received and then compare that data with the total number of applications successfully accepted and visas processed. Hence to make the entire process easy, the education department in the US analyze the factors that influence the admission of a student into colleges. The objective of this exercise is to analyze the same.


# Steps that followed :
- loding the data 
- checking the null values 
- understanding the data types 
- Univarient analysis 
- BIvarient analysis(creating cross tabs and bar charts )
## Feature Engineering
-  Label Encoders: used to transform the data into catagorical variables 
-  Standerdizing the model by standerd scalar ()
  - checking the distribution of each feature by KDE plots 
  - Standardize features by removing the mean and scaling to unit variance.
The standard score of a sample x is calculated as:
z = (x - u) / s
where u is the mean of the training samples or zero if with_mean=False, and s is the standard deviation of the training samples or one if with_std=False.
Centering and scaling happen independently on each feature by computing the relevant statistics on the samples in the training set. Mean and standard deviation are then stored to be used on later data using transform.
-  Principle component analysis :
  - Elbow method 
# Model Buiding 
- Logistic regression 
- SVM
- RandomForest
- NAviebyes
- XGBOOST Classifer


Checking for the recall and precission score of the models 
Creating a confusion matrix 
Checking for the acuracy of the model 

# Observations:
# admissions of the females are more then the males 
# most of the admission happend from Hispanic ethinicity followed by AfericanAmerican and Asian 
# the minimum GRE score for the admisson is 300 and above
# minimum GPA score to the admission 2.4 and above 
# Most of the admiited students ranked 2nd followed by 1st and 3rd and least being 4th 
# mean&min GRE score for a female,male to be admitted from Hispanic ethinicity are 638,609 and 480,300
# mean&min GRE score for a female,male to be admitted from Asian are 650,655 and 500,520
# mean&min GRE score for a female,male to be admitted from are African American 583,590 and 340,440
# mean&min GPA score for a female,male to be admitted from Hispanic ethinicity are 3.5,3.3 and 2.6,2.4
# mean&min GPA score for a female,male to be admitted from Asian are 3.5,3.4 and 2.9,2.8
# mean&min GPA score for a female,male to be admitted from are African American 3.5,3.6 and 2.6,3.0

ALL the Logistic and Naviebyes and XGB had the same Accuracy(with out CV & Tuning) 
