# Human-Activity-Recognition-using-smartphone-data-

Human Activity Recognition using Smartphone data

The objective of this project is to determine the activity of the human which is done using the data collected from 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKINGUPSTAIRS, WALKINGDOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. The main objective of the project is to classify activities into one of the six activities performed by the volunteers.

After importing the libraries and the data, we preprocessed the data by checking for duplicates, missing values and class balance. Then we performed the Exploratory data analysis (EDA) to understand and visualise the features of the data and then the final step in this project the machine learning model creation. We have performed different types of classification models link Logistic Regression, Kernel SVM model, Decision tree model and Random forest model with hyper parameter tuning and cross validation.

#### Steps involved in this project are: 
1. Importing libraries
  
2. Loading data

3. Data preprocessing
   * Checking for duplicates
   * Checking for missing values
   * Checking for class imbalance

4. Exploratory Data Analysis (EDA)
   * Analysing tBodyAccMag-mean feature
   * Analysing Angle between X-axis and gravityMean feature
   * Visualising data using PCA
   * Visualising data using t-SNE

5. ML Model
   * Logistic regression model with Hyperparameter tuning and cross validation
   * Kernel SVM model with Hyperparameter tuning and cross validation
   * Decision tree model with Hyperparameter tuning and cross validation
   * Random forest model with Hyperparameter tuning and cross validation


Accuracy
* Accuracy using Logistic Regression : 95.59%
* Accuracy using Kernel SVM : 96.59%
* Accuracy using Decision tree : 85.18%
* Accuracy using Random forest : 90.69%
