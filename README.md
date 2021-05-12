# Diabetes_Prediction_ML
This data is downloaded from Kaggle (https://www.kaggle.com/uciml/pima-indians-diabetes-database). Acknowledgements: Smith, J.W., Everhart, J.E., Dickson, W.C., Knowler, W.C., &amp; Johannes, R.S. (1988). Using the ADAP learning algorithm to forecast the onset of diabetes mellitus. In Proceedings of the Symposium on Computer Applications and Medical Care (pp. 261--265). IEEE Computer Society Press.


This project is the analysis of ‘Pima Indian Diabetes’ dataset. It consists of 9 columns. ‘Outcome’ column has only two characters namely 0 & 1 where 0 means Non-Diabetic patients and 1 means Diabetic one. 
This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database.
Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.
•	Pregnancies: Number of times pregnant
•	Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
•	BloodPressure: Diastolic blood pressure (mm Hg)
•	SkinThickness: Triceps skin fold thickness (mm)
•	Insulin: 2-Hour serum insulin (mu U/ml)
•	BMI: Body mass index (weight in kg/(height in m)^2)
•	DiabetesPedigreeFunction: Diabetes pedigree function
•	Age: Age (years)
•	Outcome: Class variable (0 or 1)
Here, I apply 
•	Logistic Regression
•	K Nearest Neighbour
•	Decision Tree
•	Random Forest
•	Naïve Bayes
•	Support Vector Machine  &
•	XGBoost Classifier
Then compare their respective accuracy scores. While calculating the accuracy scores I apply K-Fold Cross Validation (where K = 10) to get an unbiased accuracy of each of the model.
After that I plot ROC (Receiver Operating Characteristic) curve as well as calculating AUC (Area Under (ROC) Curve) score for each of the models.
Then I selected two of the highest accuracies as well as AUC scores & calculate the AIC (Akaike information criterion) score to know which of the model is better or simpler.
Finally, I’ve created a Pandas Data-frame to show the results from two of the classification model with highest accuracy scores. 
